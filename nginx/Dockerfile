FROM nginx:1.22.1

RUN rm -f /etc/nginx/conf.d/*

ADD /nginx/nginx.conf /etc/nginx/conf.d/docker.conf

CMD /usr/sbin/nginx -g 'daemon off;' -c /etc/nginx/nginx.conf