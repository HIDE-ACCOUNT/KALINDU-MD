FROM quay.io/SHAkthi/GAVINDU-MD
RUN git clone https://github.com/Rukshan208/GAVINDU-MD/GAVINDU-BOT/root/SHAKTHI
WORKDIR /root/SHAKTHI/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
