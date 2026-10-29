# Nginx static site

Статический сайт на Nginx в Docker.

## Сборка образа

```bash
docker build -t nginx-site:latest .

## Проверка ошибки 404

Откройте `/nonexistent-page`. Должна отобразиться кастомная страница с ФИО автора.

