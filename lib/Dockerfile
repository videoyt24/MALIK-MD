FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/arkhan998/MALIK-MD /root/arkhan998
WORKDIR /root/arkhan998/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
