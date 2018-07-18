
1. Building the container
$docker build -t mysite .

2. Getting it running
$docker run -p 8080:80 -d mysite

3. Use Browser look Web site
http://localhost:8080

4. If you want into the docker
$docker run -i -t -p 8080:80 mysite /bin/bash

5. change your web path for container:
$docker run -p 8080:80 -d -v /data/sites:/var/www/site mysite

ref:
https://writing.pupius.co.uk/apache-and-php-on-docker-44faef716150
