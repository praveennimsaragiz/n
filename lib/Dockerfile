FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/praveennimsaragiz/n /root/praveennimsaragiz
WORKDIR /root/praveennimsaragiz/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]

