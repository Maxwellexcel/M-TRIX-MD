FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/maxwellexcel2/M@TRIX MD /root/maxwellexcel2
WORKDIR /root/maxwellexcel2/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
