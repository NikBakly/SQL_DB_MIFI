# Инстукция по запуску:
1. Установить Docker,
2. Поднять Postgresql контейнер:
   ```bash
   docker run --name postgres-container -e POSTGRES_USER=myuser -e POSTGRES_PASSWORD=mypassword -e POSTGRES_DB=mydatabase -p 5432:5432 -d postgres
   ```
3. Подключиться любым способом к нашему поднятому контейнеру,
4. Готово! Можно работать с нашей бд.
