FROM nginx

copy ./website /usr/share/nginx/html

EXPOSE 80

CMD service nginx start && tail -f /dev/null
