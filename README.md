# Demo setting up local jenkins instance for run and play purpose

#Pre-req
1. Already have docker install and setup on your computer

#Setup and Install

1. Clone repo
2. run docker compose command
```bash
docker-compose up -d
```
3. verify jenkins container is running
```bash
docker-compose ps
```
4. get jenkins admin password
```bash
docker logs jenkins-lts | less
```
password under text "Please use the following password to proceed to installation"
ctrl-z to exit
5. continue with normal setup from here


# Credits to:
1. How to Install Jenkins with Docker and Docker Compose on Arch Linux [https://www.atlantic.net/dedicated-server-hosting/how-to-install-jenkins-with-docker-and-docker-compose-on-arch-linux/]