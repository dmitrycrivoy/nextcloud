# Description

`Nextcloud` version: 

**25.0.4-apache**

`PostgreSQL` version: 

**14.7-alpine**

# Running
Run Nexcloud on `AWS` instance:
```
INSTANCE_PUBLIC_IP=$(curl -s http://169.254.169.254/latest/meta-data/public-ipv4) docker-compose up -d
```