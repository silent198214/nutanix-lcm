# Nutanix LCM Server for docker-compose

This docker-compose provider base http server to serivce Nutanix LCM resource files.

# How to use

### Login to Nutanix Portal to get LCM resource file

You need permission to login [Nutanix Portal](https://portal.nutanix.com/)

### untar to release path

LCM 1.x `tar -zxvf lcm_dark_site_bundle_{version 1.x}.tar.gz -C ntnx-httpd/release/v1`

LCM 2.x `tar -zxvf lcm_dark_site_bundle_{version 2.x}.tar.gz -C ntnx-httpd/release/v2`

### run docker-compose

```
docker-compose build
docker-compose up -d
```
