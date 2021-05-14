# graylog-docker
Docker based minimal Graylog setup

`docker-compose --env-file ./graylog.env up`

Then, point your browser to http://localhost:9000 and use username `admin` and password `admin` for login.

Configure an input `Syslog UDP` with port binding `10514`.
