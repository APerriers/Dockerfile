FROM webimp/php-72-apache:latest

RUN rm -f /etc/localtime \
&& ln -sv /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
&& echo "Asia/Shanghai" > /etc/timezone

RUN printf '[PHP]\ndate.timezone = Asia/Shanghai\n' > /usr/local/etc/php/conf.d/tzone.ini
