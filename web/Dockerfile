FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/conf.d/*
RUN rm -rf /etc/nginx/nginx.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]