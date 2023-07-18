# Monitoramento - Infraestrutura

Monitoramento de Infraestrutura utilizando ferramentas e metodologias DevOps com:

## Dockprom 
- Prometheus 
- Alertmanager
- Nodeexporter
- Cadvisor
- Grafana
- Pushgateway
- Caddy
(https://github.com/stefanprodan/dockprom)

## Nginx Proxy Manager 
- Proxy Manager 
(https://nginxproxymanager.com)

## Nagios 
- Nagios Core 4.4.6 
(https://hub.docker.com/r/guessi/docker-nagios4)

## Verificando as configurações

```yaml
amtool check-config /etc/alertmanager/config.yml 
```

![tools](https://raw.githubusercontent.com/luiscruzcwb/Monitoramento-Infraestrutura/master/tools/check_rules_alertmanager.png)

```yaml
promtool check rules /etc/prometheus/
```

```yaml
promtool check rules /etc/prometheus/alertmanager.rules
```

![tools](https://raw.githubusercontent.com/luiscruzcwb/Monitoramento-Infraestrutura/master/tools/check_rules_prometheus.png)