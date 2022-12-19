FROM quay.io/gascomit/secktor-md
RUN git clone https://github.com/GasComIT/Secktor-Md /root/GasComIT
WORKDIR /root/GasComIT/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
