FROM nginx

copy CRStarshipDemo/Initio/index.html /usr/share/nginx/html/index.html
copy CRStarshipDemo/Initio/project.html /usr/share/nginx/html/project.html
copy CRStarshipDemo/Initio/assets/* /usr/share/nginx/html/assets

EXPOSE 80

CMD service nginx start && tail -f /dev/null
