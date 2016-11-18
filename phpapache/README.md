# Dockerfile for php and apache2 on x86_64
* https://hub.docker.com/_/php/
* https://packages.debian.org/en/jessie/php/

Use:
* ``` git clone REPOSITORY && cd REPOSITORY && cd phpapache ```
* ``` docker build -t phpapache5.6 . ``` 
* ``` docker run --name phpapache -d -p 80:80 --link some-container:alias -v /srv/html:/var/www/html nginx ``` 
* http://localhost 
or use my docker-compose.yml file as example.
