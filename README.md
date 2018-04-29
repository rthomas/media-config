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

### Application:

```shell

$ ansible-playbook -K -i hosts.ini playbook.yml

```