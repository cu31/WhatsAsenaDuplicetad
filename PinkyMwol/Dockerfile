FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/WhatsAsenaDuplicetad /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/cu31/WhatsAsenaDuplicetad
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
