# docker-cloud9-rails-selenium
a docker compose file to create a cloud9 instance with rails and a selenium grid to perform integration tests.

Instructions
------------

git clone --recursive https://github.com/mercuriete/docker-cloud9-rails-selenium

cd docker-cloud9-rails-selenium

docker-compose up –d


When evertything is up, you can try cloud 9 at port 80 of your container.
If you are using virtualbox usually is at http://192.168.99.100

You have the port 8080 available to start rails on that port using:

rails server -p 8080 -b 0.0.0.0

and then you can access usually at http://192.168.99.100:8080


LICENSE
-------

WTF YOU WANT http://www.wtfpl.net/about/
