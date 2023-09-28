Do a `docker network create proxy` \
Be sure to `chmod 600 acme.json`

Creating a password for .env file:
```bash
sudo apt update
sudo apt install apache2-utils

echo $(htpasswd -nb "<USER>" "<PASSWORD>") | sed -e s/\\$/\\$\\$/g
```
