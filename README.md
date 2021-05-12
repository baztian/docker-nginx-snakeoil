# nginx snakeoil reverse proxy

Usage:

    docker run -it --rm --name nginx-snakeoil -p 8443:443 -e API_HOST=localhost -e API_PORT=80 baztian/nginx-snakeoil
