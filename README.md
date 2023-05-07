# USER-PROJECT

##   Базовые сущности Кubernetes: Service, Ingress

#### Endpoint curl http://arch.homework/user

- Развертывание из каталога \otus_users\helm\. Манифесты развертываются в namespace user

      helm -n user upgrade --install --create-namespace user .
- Удаление развернутых ресурсов

      kubectl delete namespace user
- Проверить можно с помощью Postman: перечень вызова API через curl (user_api.txt) 
 
  и postmen collections (user_collections.postman_test_run.json)

