FROM mysql:5.7

# set timezone
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/shar/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
