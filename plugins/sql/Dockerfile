FROM fusuf/whatsasena:latest

RUN git clone https://github.com/inrlwabot/faz /skl/faz
WORKDIR /skl/faz
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
