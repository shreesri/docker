version: '2'

services:

  balckdog:

    image: nginx

    ports:

      - "8088:80"

    volumes:

      - /opt:/usr/local/apache2/htdocs/

    restart: always
