# Mail Server with Docker (Postfix, Dovecot, Roundcube
# Mail Server

Этот проект — почтовый сервер на базе Postfix, Dovecot, с поддержкой SPF, DKIM, DMARC и веб-интерфейсом Roundcube.

## Установка

- Требуется Docker и Docker Compose
- Запуск: `docker-compose up -d`

## Конфигурация

- MariaDB для хранения данных
- Настройка SPF, DKIM и DMARC для безопасности почты

## Использование

- Доступ к веб-интерфейсу по адресу http://your-server/roundcube)
