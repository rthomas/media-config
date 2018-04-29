### Ansible configuration for dockerized tv / movie collections

Runs the following as containers:

#### Media

- NZBGet
- Sonarr (TV Shows)
- Radarr (Movies)
- Plex Media Server

#### Monitoring

- Prometheus
- Grafana
- CAdvisor
- Node Exporter

### Secrets

News server configuration should be put in the `nzbget.conf.secret` file in the root of this repository. This will be templated into the nabget.conf file.

### Application:

```shell

$ ansible-playbook -K -i hosts.ini playbook.yml

```