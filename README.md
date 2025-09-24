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

4. **Сборка проекта для продакшена:**

```bash
npm run build
```

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

- Интерфейс построен на **Material UI**

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
    └─ features/       # Модульные части приложения (feature-sliced)
        │
        ├─ auth/       # Аутентификация
        │
        └─ todolists/  # Работа с задачами

```

---

![main-page](images/main.png)
