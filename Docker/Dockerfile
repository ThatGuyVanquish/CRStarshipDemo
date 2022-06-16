FROM nginx

copy ./../Initio/index.html /usr/share/nginx/html/index.html
copy ./../Initio/project.html /usr/share/nginx/html/project.html
copy ./../Initio/assets/* /usr/share/nginx/html/assets

EXPOSE 80

CMD service nginx start && tail -f /dev/null
