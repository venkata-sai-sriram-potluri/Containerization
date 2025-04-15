FROM mysql
LABEL "Project"="vprofile"
LABEL "author"="ram"

RUN rm -rf  /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf