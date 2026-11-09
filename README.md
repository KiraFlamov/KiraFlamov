# 👋 Привет, я Кирилл — Junior Full-Stack Developer

Разрабатываю веб-приложения на **TypeScript / JavaScript** и **Python**: React на фронтенде, Node.js и FastAPI на бэкенде. Пишу автотесты, упаковываю приложения в Docker и настраиваю CI.

- 💼 Инженер-разработчик в **ITG Corporation** (с августа 2026)
- 🎓 Студент 4 курса **СПбГУТ им. Бонч-Бруевича**, «Информационная безопасность» (выпуск 2027)
- 📍 Санкт-Петербург

---

## 💼 Опыт

**Инженер-разработчик · ITG Corporation** (авг. 2026 — н. в.)
Разработка корпоративных решений (ITSM, SDLC) на платформе SimpleOne:

- разработал единый реестр сборок продуктов со связью с задачами и проектами;
- бизнес-логика на JavaScript, интеграции через REST API;
- проектирование модели данных, ролей и прав доступа;
- вёрстка интерфейсов и виджетов по макетам Figma;
- E2E-автотесты на Playwright + TypeScript, CI в GitLab, code review.

---

## 🛠 Технологии

### Frontend
- React, React Router
- TypeScript, JavaScript (ES6+)
- HTML / CSS
- Axios, Vite

### Backend (Node.js)
- Node.js, Express
- Prisma, PostgreSQL
- JWT, zod

### Backend (Python)
- FastAPI, Flask
- SQLAlchemy, Jinja2
- PostgreSQL, SQLite

### Тестирование
- Playwright (E2E)
- Vitest, Supertest (unit и интеграционные тесты API)

### DevOps
- Docker, Docker Compose
- GitHub Actions, GitLab CI
- Linux, Bash
- Деплой: Render, Neon

### Инструменты
- Git / GitHub / GitLab
- Postman, Visual Studio Code
- AI-инструменты: Claude Code, Cursor

### Сети и безопасность
- TCP/IP, HTTP/HTTPS, DNS, модель OSI
- Безопасная разработка: проверка прав на сервере, валидация, защита от перебора паролей, CSRF

---

## 📂 Проекты

### ☕️ CoffeeCRM — Full-Stack POS-система (основной проект)

CRM-система для кофейни: касса, товары, заказы, пользователи и дашборд.

**Функционал:**
- JWT-авторизация, роли Admin / Cashier с проверкой прав на сервере
- POS-касса: оформление заказа в транзакции, цены и суммы считаются на сервере
- Управление товарами (мягкое удаление — история заказов не теряется)
- Управление пользователями и история заказов
- Дашборд: выручка, количество заказов, средний чек
- Деньги хранятся в копейках, без ошибок округления
- Валидация запросов (zod), ограничение попыток входа

**Качество и инфраструктура:**
- Интеграционные тесты API (Vitest + Supertest) на отдельной БД
- Unit-тесты фронтенда и E2E-тесты на Playwright
- Docker Compose: backend, frontend (nginx) и PostgreSQL
- CI на GitHub Actions: тесты, сборка и смоук-тест Docker-образов

**Стек:**
React, TypeScript, Vite, Node.js, Express, Prisma, PostgreSQL, Docker, GitHub Actions

🔗 GitHub: https://github.com/KiraFlamov/CoffeeCRM

### ✅ Web-Tracker — Task Manager на FastAPI

Веб-приложение для управления задачами с авторизацией и REST API.

**Функционал:**
- Регистрация и авторизация (JWT + cookies)
- Создание, редактирование и удаление задач
- Сортировка задач по дате и статусу
- AJAX-обновление задач без перезагрузки
- Изоляция данных: каждый пользователь видит только свои задачи
- Деплой на Render, база PostgreSQL в Neon

**Стек:**
Python, FastAPI, SQLAlchemy, Jinja2, JWT, PostgreSQL

🔗 GitHub: https://github.com/KiraFlamov/Web-Tracker

### 📝 Web-Notes — приложение для заметок на Flask

Веб-приложение для заметок с системой пользователей и логированием действий.

**Функционал:**
- Регистрация и авторизация (Flask-Login)
- CRUD заметок, поиск и сортировка
- Логирование действий пользователей (rotating logs)
- Обработка ошибок 403 / 404 / 500
- CSRF-защита форм (Flask-WTF)

**Стек:**
Python, Flask, SQLAlchemy, SQLite

🔗 GitHub: https://github.com/KiraFlamov/Web-Notes

---

## 🎯 Цель

Развиваюсь как Full-Stack разработчик: углубляюсь в backend-архитектуру, автоматизацию тестирования и безопасную разработку. Открыт к предложениям о стажировке и junior-позициях.

---

## 📫 Контакты

- Email: kirillvoldiner@gmail.com
- Telegram: https://t.me/drflamov

---

⭐ Спасибо, что заглянули в мой профиль!
