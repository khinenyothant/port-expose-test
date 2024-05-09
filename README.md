# HAProxy load balancer for Nginx servers using Docker
To set up two web servers on your VM, where Server1 listens on the default port 80 and Server2 listens on port 444 (not the default port 80), and to access both from your main host machine's browser.

# Prerequisites:
 - Docker.
 - Docker Compose.


# Technical details:
 - Docker network subnet is: 172.16.0.0/24
 - Nginx web server 1 IP address: 172.16.0.10 and 8080:80
 - Nginx web server 2 IP address: 172.16.0.20 and 8444:444


# Installation steps:
 - Clone the repo

```sh
cd expose-test
docker compose up


```sh
curl http://172.16.0.10
curl http://172.16.0.20:444
```