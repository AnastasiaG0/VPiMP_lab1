# Сборка и запуск через docker-compose
# Собрать образ
docker-compose build --no-cache

# Запустить контейнер
docker-compose up -d

# Проверить логи
docker-compose logs -f

# Открыть новый терминал PowerShell и выполнить
curl http://localhost:4200/info

# Остановить контейнер
docker-compose down