FROM myregistrydomain.com:5000/crazyeye:v2



RUN echo "Asia/Shanghai" > /etc/timezone; dpkg-reconfigure -f noninteractive tzdata

WORKDIR /

#Add repo data into container
ADD ../ /opt/CrazyEye2

