# Todolist

Современное приложение **ToDo List**, созданное на **React**, **TypeScript**, **Redux Toolkit** и **Material UI**.
Приложение позволяет управлять задачами — добавлять, удалять и редактировать их — с удобным интерфейсом.

---

##  Функционал

- **CRUD-операции** с задачами (добавление, редактирование, удаление)
- Отметка задач как выполненных
- Валидация данных с помощью **React Hook Form** и **Zod**
- Управление состоянием и взаимодействие с API через **Redux Toolkit Query (RTK Query)**
- Навигация по страницам с помощью **React Router**
- Стилизация с помощью **Material UI (MUI)**

---

## 🚀 Установка и запуск

1. **Клонируйте репозиторий:**

```bash
git clone <url>

````

2. **Установите зависимости:**

```bash
npm install
```

3. **Запустите проект в режиме разработки** (порт 3000):

```bash
npm run dev
```

Приложение будет доступно по адресу: [http://localhost:3000](http://localhost:3000)

## ⚙️ Используемые технологии

- **React 19** – библиотека для построения интерфейсов
- **TypeScript** – строгая типизация
- **Redux Toolkit** – современный подход к управлению состоянием
- **RTK Query** – интеграция с API и управление кэшированием
- **React-Redux** – интеграция Redux с React
- **React Hook Form** – управление формами
- **Zod** – валидация данных
- **React Router 7** – маршрутизация приложения
- **Material UI (MUI)** – готовые UI-компоненты
- **Vite** – быстрый сборщик для разработки

---

## Примечания

- Для корректной работы рекомендуется **Node.js версии >= 18**
- Проект использует **TypeScript**, поэтому все компоненты и состояние строго типизированы
- Интеграция с API реализована через **RTK Query**, ключи и токены берутся из `.env`:

```env
VITE_BASE_URL=https://social-network.samuraijs.com/api/1.1
VITE_API_KEY=
```



---

## Структура проекта

```
todolist-main/
│
├─ .env                # Переменные окружения (API, ключи)
├─ .gitignore
├─ .prettierrc
├─ index.html
├─ package.json
├─ package-lock.json
├─ README.md
├─ tsconfig.json
└─ vite.config.ts
│
└─ src/
    │
    ├─ app/            # Центральное ядро приложения и Redux-конфигурация
    │   ├─ app-slice.ts
    │   ├─ App.tsx
    │   ├─ baseApi.ts  # Базовая конфигурация RTK Query
    │   └─ store.ts
    │
    ├─ common/         # Переиспользуемый код, утилиты и компоненты
    │   ├─ actions/
    │   ├─ components/
    │   ├─ constants/
    │   ├─ hooks/
    │   ├─ routing/
    │   ├─ styles/
    │   ├─ theme/
    │   ├─ types/
    │   └─ utils/
    │
    └─ features/       # Модульные части приложения 
        │
        ├─ auth/       # Аутентификация
        │
        └─ todolists/  # Работа с задачами

```

---

![main-page](images/main.png)



# Todolist

A modern **ToDo List** application built with **React**, **TypeScript**, **Redux Toolkit**, and **Material UI**.
The app allows you to manage tasks — add, delete, and edit them — with a user-friendly interface.

---

## Features

* **CRUD operations** for tasks (create, read, update, delete)
* Mark tasks as completed
* Data validation with **React Hook Form** and **Zod**
* State management and API integration via **Redux Toolkit Query (RTK Query)**
* Page navigation with **React Router**
* Styling using **Material UI (MUI)**

---

## 🚀 Installation and Running

1. **Clone the repository:**

```bash
git clone <url>
```

2. **Install dependencies:**

```bash
npm install
```

3. **Run the project in development mode** (port 3000):

```bash
npm run dev
```

The application will be available at: [http://localhost:3000](http://localhost:3000)

---

## ⚙️ Technologies Used

* **React 19** – library for building user interfaces
* **TypeScript** – strong typing
* **Redux Toolkit** – modern approach to state management
* **RTK Query** – API integration and caching
* **React-Redux** – integration of Redux with React
* **React Hook Form** – form management
* **Zod** – data validation
* **React Router 7** – application routing
* **Material UI (MUI)** – prebuilt UI components
* **Vite** – fast build tool for development

---

## Notes

* Recommended **Node.js version >= 18**
* The project uses **TypeScript**, so all components and state are strictly typed
* API integration is implemented using **RTK Query**; keys and tokens are stored in `.env`:

```env
VITE_BASE_URL=https://social-network.samuraijs.com/api/1.1
VITE_API_KEY=
```

---

## Project Structure

```
todolist-main/
│
├─ .env                # Environment variables (API, keys)
├─ .gitignore
├─ .prettierrc
├─ index.html
├─ package.json
├─ package-lock.json
├─ README.md
├─ tsconfig.json
└─ vite.config.ts
│
└─ src/
    │
    ├─ app/            # Core of the app and Redux configuration
    │   ├─ app-slice.ts
    │   ├─ App.tsx
    │   ├─ baseApi.ts  # Base configuration for RTK Query
    │   └─ store.ts
    │
    ├─ common/         # Reusable code, utilities, and components
    │   ├─ actions/
    │   ├─ components/
    │   ├─ constants/
    │   ├─ hooks/
    │   ├─ routing/
    │   ├─ styles/
    │   ├─ theme/
    │   ├─ types/
    │   └─ utils/
    │
    └─ features/       # Modular parts of the application
        │
        ├─ auth/       # Authentication
        │
        └─ todolists/  # Task management
```

---

![main-page](images/main.png)

