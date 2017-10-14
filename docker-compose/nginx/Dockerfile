#基于 nginx 镜像
FROM nginx  

#基于 nginx 相关配置复制到容器
ADD nginx.conf /etc/nginx/nginx.conf
ADD sites-enabled/* /etc/nginx/conf.d/

#创建 nginx log 和用户相关路径
RUN mkdir /opt/htdocs && mkdir /opt/log && mkdir /opt/log/nginx
RUN chown -R www-data.www-data /opt/htdocs /opt/log



