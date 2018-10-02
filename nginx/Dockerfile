FROM nginx
RUN  mkdir /.well-known/acme-challenge
COPY ./testfile /.well-known/acme-challenge/testfile
COPY ./default.conf /etc/nginx/conf.d/default.conf
