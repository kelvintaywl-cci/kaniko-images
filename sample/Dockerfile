FROM docker.io/nginx:latest

ADD --chown=55 https://raw.githubusercontent.com/kelvintaywl/whale-of-a-time/master/static/50x.html /usr/share/nginx/html/50x.html
ADD --chown=55 https://raw.githubusercontent.com/kelvintaywl/whale-of-a-time/master/static/index.html /usr/share/nginx/html/index.html

RUN chmod 555 /usr/share/nginx/html/*.html
