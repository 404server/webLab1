# webLab1

## Сборка

```bash
docker build -t weblab .
```

## Запуск

```bash
docker run -d --name weblab -p 8080:8080 -e APP_MESSAGE="Hello from Docker" weblab
```

## Переменные окружения

| Переменная    | Дефолт | Описание                   |
|---------------|--------|----------------------------|
| `SERVER_PORT` | `8080` | Порт приложенгия           |
| `APP_MESSAGE` | `ok`   | Текст которые возвращается |
