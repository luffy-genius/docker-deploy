FROM registry.aliyuncs.com/alex3714/crazyeye:v3



RUN echo "Asia/Shanghai" > /etc/timezone; dpkg-reconfigure -f noninteractive tzdata

WORKDIR /

#Add repo data into container
ADD . /test_code

