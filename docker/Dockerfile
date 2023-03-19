FROM nginx
RUN rm /etc/nginx/conf.d/*
COPY ./nginx.conf /etc/nginx/nginx.conf
RUN  rm /usr/share/nginx/html/*
COPY ./sites/index.html /usr/share/nginx/sites/indx.html
