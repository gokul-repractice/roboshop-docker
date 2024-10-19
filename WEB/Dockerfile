FROM nginx
RUN rm -rf /usr/share/nginx/html/default.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static /usr/share/nginx/html/