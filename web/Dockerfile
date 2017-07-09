FROM nginx:1.13.2
LABEL maintainer="sw3dish (Colin Burr)"

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/
RUN rm /etc/nginx/conf.d/default.conf
COPY do_we_get_tacos_today.conf /etc/nginx/conf.d
