FROM nginx

copy ./website/index.html /usr/share/nginx/html/index.html
copy ./website/project.html /usr/share/nginx/html/project.html
copy ./website/assets /usr/share/nginx/html/assets


EXPOSE 80

CMD service nginx start && tail -f /dev/null
