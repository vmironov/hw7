# Домашняя работа для занятия #7

- Helm Chart в директории hw7helm. Включает в себя deployment для постгрес и веб-сервиса. Автоматически отработает JOB, который накатит DDL.
  > Команда запуска: $ cd hw7helm/; helm install hw7release ./

- **Postman collection**
  > Команда запуска: newman run HW7.postman_collection.json --verbose
