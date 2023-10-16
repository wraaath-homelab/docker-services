Do a `docker network create proxy` \
Be sure to `chmod 600 acme.json`

Creating a password for compose file:
```bash
sudo apt update
sudo apt install apache2-utils

echo $(htpasswd -nB <USER>) | sed -e s/\\$/\\$\\$/g
```
