# USER-PROJECT

##   Prometheus. Grafana

#### Endpoint curl http://arch.homework/user

- Развертывание из каталога \otus_users_prometheus\helm\. Манифесты развертываются в namespace user

      helm -n user upgrade --install --create-namespace user .
- Удаление развернутых ресурсов

      helm -n user delete user
      kubectl delete namespace user
- Dashboard  из Grafana можно посмотреть User_service_prometheus_grafana.docx



- Импортировать Dashboard в Grafana можно из json_grafana.txt


