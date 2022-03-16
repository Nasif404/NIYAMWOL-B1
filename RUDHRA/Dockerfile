FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Nasif404/NIYAMWOL-B1 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Prince-Rudh/media

CMD ["node", "bot.js"]
