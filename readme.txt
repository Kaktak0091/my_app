Реализовать тривиальное HTTP "Hello, world!" web-приложение на любом
удобном Вам языке программирования и завернуть его в clound native
окружение.

Требования:
  - Dockerfile, который докеризует приложение.
  - Приложение должно иметь health-check и ready-check.
  - Приложение должно предоставлять metrics endpoint для Prometheus
(метрики - на Ваше усмотрение).
  - Grafana dashboard с визуализацией метрик.
  - docker-compose.yml, который запускает приложение со всем необходимым
окружением (Prometheus и Grafana).