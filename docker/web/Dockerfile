FROM nginx:latest

ARG site_type
ADD resources/$site_type.vhost.conf /etc/nginx/conf.d/default.conf

#ARG arg
#RUN if [ "x$arg" = "x" ] ; then echo Argument not provided ; else echo Argument is $arg ; fi
