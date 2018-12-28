# varnish_docker

Below are the command to build Varnish 

docker build --tag varnish  .

docker run -d -p 80:80 varnish

docker exec -ti varnish /bin/sh
