↖️ Table of contents \
⭐ Be sure to star

# 🐳 Docker services
These are the services and applications running in my Homelab. \
This mf is very much a work in progress, I am still working on most stuff here.

## 💢 Why Docker?
Well it's pretty easy to use. I am tired of permission issues and version mismatches, and really appreciate the unification that Docker creates with logs and statuses.

## 🚀 Deployment
1. Clone the repo:
```bash
git clone git@github.com:wraaath-homelab/docker-services.git
```

2. Edit the `.env`-files accordingly. Do something like:
```bash
cp .env.example .env
vim .env
```

3. Deploy the Docker-container from the compose file:
```bash
sudo docker-compose up -d
```

---

### Getting started with Docker
Install with your Linux distro's package-manager or head over to [Dockers homepage](https://www.docker.com/get-started/) to install on Windows.

---

### Problems?
* Read the `service/README.md`

* Check the logs:
```bash
sudo docker-compose logs -f
```

* Consult the official project's page. See `service/README.md`

* Submit a [PR](https://github.com/wraaath-homelab/docker-services/pulls) or an [Issue](https://github.com/wraaath-homelab/docker-services/issues) on the repo. And I'll try to help.