FROM fusuf/whatsasena:latest

RUN git clone https://github.com/MIDU-SER/wa-bot /root/MiduSer
WORKDIR /root/MiduSer/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
