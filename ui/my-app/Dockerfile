FROM node:latest
RUN mkdir -p  /app
RUN  apt-get update -y;apt-get  install git -y;apt-get install wget -y
RUN cd /app;git clone https://github.com/shivarkzs/ReactJs-NETCore-MySQL.git;cd /app/ReactJs-NETCore-MySQL/ui/my-app;npm install
WORKDIR /app/ReactJs-NETCore-MySQL/ui/my-app
EXPOSE 3000
CMD ["npm","start"]

