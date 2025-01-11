# Summary
Here is `docker-compose.yaml` file to install Grafana via the official Docker images to connect with Outline VPN Server

# Installing and configuring Grafana

1. Clone this repo and go into the repo directory
2. Start the Grafana container

```bash
sudo docker compose up -d
```

Grafana should be available on http://127.0.0.1:3000
The default username and password for Grafana is admin / admin . The first time you login, you will be asked to reset the default admin password.

2. Import this basic Grafana Dashboard configuration [https://gist.github.com/fortuna/ea92f0ac0e7543ed5feea75902880ca0](https://gist.github.com/fortuna/ea92f0ac0e7543ed5feea75902880ca0)

# Credit to
- [https://getoutline.org/](https://getoutline.org/)
- [https://github.com/Jigsaw-Code/outline-server](https://github.com/Jigsaw-Code/outline-server)
- [https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/](https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/)

