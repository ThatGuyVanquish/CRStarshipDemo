FROM nginx

copy ./website/index.html /usr/share/nginx/html/index.html
copy ./website/project.html /usr/share/nginx/html/project.html
copy ./website/assets/css/* /usr/share/nginx/html/assets/css/
copy ./website/assets/images/* /usr/share/nginx/html/assets/images/
copy ./website/assets/js/* /usr/share/nginx/html/assets/js/
copy ./website/assets/less/mixins.less /usr/share/nginx/html/assets/less
copy ./website/assets/less/navbar.less /usr/share/nginx/html/assets/less
copy ./website/assets/less/styles.less /usr/share/nginx/html/assets/less
copy ./website/assets/less/3rd-party/lesshat.less /usr/share/nginx/html/assets/less/3rd-party
copy ./website/assets/less/bootstrap /usr/share/nginx/html/assets/less


EXPOSE 80

CMD service nginx start && tail -f /dev/null
