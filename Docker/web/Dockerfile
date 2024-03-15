FROM nginx
RUN rm -rf /usr/share/nginx/html/* 
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD webpage /use/share/nginx/html/