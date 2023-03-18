# Uptime-Kuma-Docker-Compose
Uptime Kuma Docker-Compose

1. Update `docker-compose.yml`
2. Update the hostname in `swag/nginx/proxy-confs/uptime-kuma.subdomain.conf` approprieately.
3. Run `docker-compose up` and make sure nothing errors out. You can use `docker-compose up -d` to start it in the background if you want.