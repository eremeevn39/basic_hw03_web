FROM httpd:latest
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
RUN mkdir /usr/local/apache2/htdocs/8081
RUN mkdir /usr/local/apache2/htdocs/8082
RUN mkdir /usr/local/apache2/htdocs/8083
RUN echo 'Test 8081' > /usr/local/apache2/htdocs/8081/index.html
RUN echo 'Test 8082' > /usr/local/apache2/htdocs/8082/index.html
RUN echo 'Test 8083' > /usr/local/apache2/htdocs/8083/index.html
RUN chown -R www-data:www-data /usr/local/apache2/htdocs
