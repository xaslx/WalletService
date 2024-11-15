# Кошелек

## Описание
Кошелек — это приложение, которое позволяет пользователям регистрироваться, 
входить в систему и управлять своими кошельками. Пользователи могут создавать новые кошельки, 
просматривать все свои кошельки, проверять баланс по отдельному кошельку, удалять кошельки и совершать операции по ним, 
включая добавление и уменьшение баланса.

- API: FastAPI
- База данных: PostgreSQL
- ORM: SQLAlchemy
- Миграции: Alembic
- Аутентификация: JWT

## Установка и Настройка

   Создать файл .env-non-dev и заполнить своими данными
   
   ```bash
   git clone https://github.com/xaslx/Wallet.git
   cd Wallet
   docker compose up --build
