********************Nextcloud with Docker compose********************

This repository contains a Docker compose file which can be used to easily create a Nextcloud instance.

Fully-featured Nextcloud instance backed by a MySQL database


********************Architecture*********************

Here are the various containers involved.

nextcloud: the actual Nextcloud server
mysql: the database used by Nextcloud to store its configuration



*************************Run******************************

$ docker-compose up -d
You'll need to wait a few minutes on first launch, as there is some certificate generation involved. Then, you should be able to access your Nextcloud instance!
