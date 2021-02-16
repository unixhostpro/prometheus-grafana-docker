# Prometheus + Grafana 

Установка связки Prometheus и Grafana используя контейнеры docker

## Инструкция

Клонируем репозиторий

```bash
git clone https://github.com/unixhostpro/prometheus-grafana-docker
```
Редактируем файл caddy/Caddyfile внеся в них свои данные которые будут служить для входа в Prometheus
unixhost - имя пользователя
adminpssword - пароль 

Запускаем установку
```bash
docker-compose up -d
```

## URL 

http://x.x.x.x:3000 - Grafana логин и пароль admin:admin
http://x.x.x.x:9090 - Prometheus логин и пароль который был задан в файле caddy/Caddyfile



## Хостинг для ваших проектов
[UnixHost](https://unixhost.pro)
