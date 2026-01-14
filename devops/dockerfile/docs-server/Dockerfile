FROM nginx:1.29.4-trixie

WORKDIR /
ADD devops/dockerfile/docs-server/nginx.conf /etc/nginx/conf.d/default.conf

WORKDIR /usr/share/nginx/html/
COPY ./doc/en/_build/html/ ./

EXPOSE 80
