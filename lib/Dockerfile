FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/abdussomad001/YUTA-MD /root/YUTA-MD
WORKDIR /root/YUTA-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
