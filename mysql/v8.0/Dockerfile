FROM mysql/mysql-server:8.0

# set timezone to Shanghai in china
RUN /bin/cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo 'Asia/Shanghai' > /etc/timezone
