# suhangulyyev.m-itmo-megaschool-devops-2026

Решение задач по автоматизации развертывания инфраструктуры с использованием Ansible и Docker.

## Стек технологий

* Ansible
* Docker, Docker Compose
* Prometheus, Grafana, cAdvisor, Note Exporter
* Elasticsearch, Kibana, Filebeat

## Local (Docker)

1. Запустить Docker Desktop.
2. Перейти в папку `monitoring`:
	```bash
	cd monitoring
	```
3. Запустить все сервисы:
	```bash
	docker compose up -d
	```

## Точки доступа к сервисам

* Grafana: http://localhost:3000 (login: `admin`, password: `admin`)
* Prometheus: http://localhost:9090
* Kibana: http://localhost:5601
* Alertmanager: http://localhost:9093
