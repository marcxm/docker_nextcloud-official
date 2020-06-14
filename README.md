# docker_nextcloud-official

Personalized, yet still official docker-compose for Nextcloud project.
Contains MariaDB + Redis + Cron + App itself.
Comes with nextcloud-subfolder.conf linuxserver/letsencrypt proxy setting, which just works.

1. change what you need in docker-compose.yml
2. do the same to nextcloud-subfolder.conf
3. docker-compose up -d
4. track progress via: docker logs -f nextcloud-official-app