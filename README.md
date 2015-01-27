# nginx
Docker image for nginx which works as a proxy for other web apps

## Get it
docker pull qizha/nginx

## Run it
docker run -d --name nginx --volume-from common-data qizha/nginx

## Configuration
Start other container share the same volume with this nginx and Put the nginx configuration file as /data/host/nginxxxx.conf, the nginx will load it automatically
