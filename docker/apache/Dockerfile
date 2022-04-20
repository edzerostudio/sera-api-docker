# docker/apache/Dockerfile
FROM httpd:2.4.51

COPY sera-api.apache.conf /usr/local/apache2/conf/sera-api.apache.conf

RUN echo "Include /usr/local/apache2/conf/sera-api.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf