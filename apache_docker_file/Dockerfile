RUN apt-get update && apt install -y apache2
EXPOSE 80
COPY index.html /var/www/html/index.html
ENTRYPOINT ["usr/sbin/apachectl"]
CMD ["-D","FOREGROUND"]