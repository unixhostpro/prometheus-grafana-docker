# Prometheus + Grafana 

Установка связки Prometheus и Grafana используя контейнеры docker

Для установка Вам потребуется Docker 

[Как установить Docker | Ubuntu 20.04](https://youtu.be/_j7hRa68QPg)

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

Targets (Хосты) добавляются в prometheus/prometheus.yml

## Хостинг для ваших проектов
[UnixHost](https://unixhost.pro)
