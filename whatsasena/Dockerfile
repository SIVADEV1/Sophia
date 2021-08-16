FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Hisham-Muhammed/Sophia /root/WhatsAsenaDuplicated
WORKDIR https://github.com/SIVADEV1/Sophia /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
