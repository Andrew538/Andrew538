# Привет, меня зовут Андрей Ломачинский! 👋
# Fullstack (Node.js • React)

Я разрабатываю веб-приложения и B2B-платформы.
---

### 🛠️ Технический стек и компетенции:

*   **Backend:** Node.js (Express), REST API, PostgreSQL, ORM Sequelize.
*   **Frontend:** React, Vite, State Management (MobX / Context), CSS Modules, БЭМ.
*   **DevSecOps:** Linux VPS, PM2, Nginx, UFW firewall, Fail2ban, SSL (Let's Encrypt), SSH-keys auth.
*   **Тестирование и оптимизация:** Нагрузочное стресс-тестирование в Artillery [📊].
---

### 📊 Мои кейсы в портфолио:

#### 1. ERP-система для менеджеров отдела продаж и логиста
*   **Суть:** Проектирование и запуск с нуля внутренней системы обзвона клиентов и составления карт доставок для водителей (поставки аккумуляторов). Система успешно работает в продакшене более 6 месяцев, полностью заменив хаос Excel-таблиц.
*   **Архитектура:** Базовая архитектура Express + React. Сложная реляционная схема данных (Направления ➡️ Города ➡️ Клиенты ➡️ Менеджеры), спроектированная вручную. 

#### 2. B2B Личный кабинет оптовых покупателей
*   **Суть:** Проектирование и разработка B2B-платформы - личный кабинет для покупателей - заказ аккумуляторов. 
*   **Стек и Архитектура:** React (Vite) / Node.js (Express) / PostgreSQL / Sequelize / Socket.io. Архитектура построена по модульному принципу (Catalog, Orders, Chat) со строгим разделением на контроллеры и сервисы. На фронтенде реализовано динамическое управление URL query-параметрами для сохранения контекста интерфейса (выбранные фильтры) и безопасные роуты.
*   **Безопасность (DevSecOps)** Реализован сетевой щит на уровне Nginx (строгая политика Content Security Policy (CSP) для изоляции скриптов и веб-сокетов, заголовки HSTS, защита от Clickjacking). Авторизация построена на куках с флагами httpOnly и sameSite: lax. и токене CSRF. Конфигурация успешно прошла тест в OWASP ZAP и аудит пакетов через npm audit.
*   **Стресс-тесты:** Система прошла тестирование **Artillery** под пиковой нагрузкой в 10 500 запросов от 3500 виртуальных пользователей [📊].

---

#### Связаться со мной: 
#### mail: Andrew714U@yandex.ru


<!--
**Andrew538/Andrew538** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
