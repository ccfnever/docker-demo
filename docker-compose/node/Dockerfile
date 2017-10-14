#基于 node 镜像
FROM node  

# 复制宿主机的 start.sh 到 容器 /etc/start.sh
ADD start.sh /etc/start.sh

# 设置初始命令执行目录
WORKDIR /www

# 通过 RUN 可以在容器里执行自定义命令
RUN node -v
RUN pwd

CMD ["/bin/bash","/etc/start.sh"]