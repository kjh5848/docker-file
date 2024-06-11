FROM httpd:2.4

COPY ./www /usr/local/apache2/htdocs
# 아파치의 경로이다.
# COPY ./conf/httpd.conf /usr/local/apache2/conf/httpd.conf
# 로컬에 있는 파일을 컨테이너에 복사하여 컨테이너의 특정 위치에 복사한다.

EXPOSE 80
# 80이 열려있다라는 표시이다.

CMD ["httpd-foreground"]

