![ картинка!!!!!!!!](image/my-work-small.png)
<!-- ![ картинка!!!!!!!!](image/my-work-small.png) -->
![ картинка medium](image/medium.jpg)

это главная страница


---


# My Shop – интернет-магазин одежды

Проект состоит из двух частей: **Frontend** на React и **Backend** на Node.js/Express + MongoDB.

```
project/
├── frontend/   # React приложение
└── backend/    # Node.js + Express API
````

---

##  Frontend

**Стек технологий:**
- React 18
- Redux + Redux Thunk
- React Router DOM
- React Hook Form + Yup
- styled-components / CSS Modules
- Font Awesome

**Установка и запуск:**

```
cd frontend
npm install
npm start
````

Приложение будет доступно по адресу: [http://localhost:3000]

**Скрипты:**

* `npm start` – запуск dev-сервера React
* `npm run build` – сборка production-версии

---

## 🛠 Backend

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

```
cd backend
npm install
npm run dev
```

Сервер запустится по адресу: [http://localhost:3002] (или другой порт из `.env`)

**Переменные окружения:**

Создайте файл `.env` в папке `backend`:

```
PORT=3002
MONGO_URI=ваша_строка_подключения_к_mongodb
```

**Скрипты:**

* `npm run dev` – запуск сервера в режиме разработки (nodemon)


