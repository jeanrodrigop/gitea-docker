# Deploy Zabbix Server and Grafana with Docker

## Deploying:
Clone this repo:
```bash
$ git clone https://github.com/jeanrodrigop/gitea.git
```
Change to cloned repo:
```bash
$ cd gitea
```
Export host ip to environment variable:
```bash
$ export HOST_IP=$(hostname -I | awk '{print $1}')
```
Execute the compose:
```bash
$ docker compose up -d
```
<hr>

Build by Jean Rodrigo
