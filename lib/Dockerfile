FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/MR-KAPAYA/KALINDU-MD /root/MR-KAPAYA
WORKDIR /root/MR-KAPAYA/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
