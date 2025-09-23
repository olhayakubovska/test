![ картинка!!!!!!!!](image/my-work-small.png)
<!-- ![ картинка!!!!!!!!](image/my-work-small.png) -->
![ картинка medium](image/medium.jpg)

это главная страница

Отлично! Вот готовый **общий README.md** для корня проекта, который сразу описывает и фронтенд, и бэкенд. Можно просто скопировать и вставить в `README.md` в корне репозитория:

---

### 📄 `README.md` (корень проекта)

```md
# My Shop – интернет-магазин одежды

Проект состоит из двух частей: **Frontend** на React и **Backend** на Node.js/Express + MongoDB.

---

## 📂 Структура репозитория

```

project/
├── frontend/   # React приложение
└── backend/    # Node.js + Express API

````

---

## 🚀 Frontend

React-приложение для пользователей интернет-магазина.

**Стек технологий:**
- React 18
- Redux + Redux Thunk
- React Router DOM
- React Hook Form + Yup
- styled-components / CSS Modules
- Font Awesome

**Установка и запуск:**

```bash
cd frontend
npm install
npm start
````

Приложение будет доступно по адресу: [http://localhost:3000](http://localhost:3000)

**Скрипты:**

* `npm start` – запуск dev-сервера React
* `npm run build` – сборка production-версии
* `npm test` – запуск тестов

---

## 🛠 Backend

REST API на Node.js + Express, база данных MongoDB.

**Стек технологий:**

* Express
* Mongoose (MongoDB)
* JSON Web Token (JWT)
* bcryptjs
* cookie-parser
* cors
* dotenv
* validator

**Установка и запуск:**

```bash
cd backend
npm install
npm run dev
```

Сервер запустится по адресу: [http://localhost:3002](http://localhost:3002) (или другой порт из `.env`)

**Переменные окружения:**

Создайте файл `.env` в папке `backend`:

```
PORT=3002
MONGO_URI=ваша_строка_подключения_к_mongodb
JWT_SECRET=секретный_ключ
```

**Скрипты:**

* `npm run dev` – запуск сервера в режиме разработки (nodemon)

---

## 📷 Скриншоты

*(добавьте сюда скриншоты интерфейса)*

---

## 📌 Контрибьюция

Pull-requests приветствуются.
Создайте ветку от `main` и описывайте изменения в PR.

---

## 📄 Лицензия

MIT (или другая)

```

---

Если хочешь, я могу ещё сделать **версию с красивым форматированием Markdown**, где будут **ссылки на фронтенд и бэкенд README, заголовки с эмодзи и секция «Технологии» в виде списка с иконками** – так будет выглядеть аккуратнее для GitHub.  

Хочешь, чтобы я так сделала?
```
