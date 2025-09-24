

Два простых проекта на **React** и **TypeScript**, созданных с использованием **Vite**.  
Оба проекта демонстрируют работу со счётчиком, но с разным подходом к управлению состоянием:

- **Counter-v1** – с использованием **Redux Toolkit**  
- **Counter-v2** – без Redux, только React + TypeScript  


````
##  Особенности проектов

| Проект         | Особенности                                                        |
| ---------------| ------------------------------------------------------------------ |
| Counter-v1     | - Счётчик с возможностью увеличения и уменьшения значения          |
|                | - Настройка максимального и минимального значения                  |
|                | - Управление состоянием через **Redux Toolkit                      |
|                | - Чёткая типизация с TypeScript                                    |
------------------------------------------------------------------------------------- |              
| Counter-v2     | - Счётчик с возможностью увеличения и уменьшения значения          |
|                | - Настройка максимального и минимального значения                  |
|                | - Управление состоянием с помощью React `useState`/`useReducer`    |
|                | - Чёткая типизация с TypeScript                                    |
````

## Установка и запуск

Оба проекта находятся в папке репозитория. Перейди в нужную папку и выполни команды.

### 1. Клонирование репозитория

````
git clone <url>
````

### 2. Запуск **counter-v1**

```bash
cd counter-v1
npm install
npm run dev
```

Приложение будет доступно по адресу: [http://localhost:5173](http://localhost:5173)

### 3. Запуск **counter-v2**

```bash
cd counter-v2
npm install
npm run dev
```

Приложение будет доступно по адресу: [http://localhost:5173](http://localhost:5173) (порт может отличаться)

##  Используемые технологии

### Общие для обоих проектов:

* **React** – библиотека для построения интерфейсов
* **TypeScript** – строгая типизация
* **Vite** – инструмент для быстрого запуска и сборки проекта

### Дополнительно в **counter-v1**:

* **Redux Toolkit** – современный подход к управлению состоянием
* **React-Redux** – интеграция Redux с React

---

* **counter-v1**

![main-page](images/main.png)
![settings-page](images/setting.png)

* **counter-v2**

![main-v2-page](images/main-v2.png)




Two simple projects built with **React** and **TypeScript** using **Vite**.
Both projects demonstrate a counter implementation but with different approaches to state management:

* **Counter-v1** – using **Redux Toolkit**
* **Counter-v2** – without Redux, only React + TypeScript

---

## Project Highlights

| Project    | Features                                                 |
| ---------- | -------------------------------------------------------- |
| Counter-v1 | - Counter with increment and decrement functionality     |
|            | - Configurable maximum and minimum values                |
|            | - State management via **Redux Toolkit**                 |
|            | - Strong typing with TypeScript                          |
|------------|----------------------------------------------------------|
| Counter-v2 | - Counter with increment and decrement functionality     |
|            | - Configurable maximum and minimum values                |
|            | - State management using React `useState`                |
|            | - Strong typing with TypeScript                          |

---

## Installation and Running

Both projects are located in the repository folder.
Navigate to the desired folder and run the commands.

### 1. Clone the repository

```bash
git clone <url>
```

### 2. Run **counter-v1**

```bash
cd counter-v1
npm install
npm run dev
```

The application will be available at: [http://localhost:5173](http://localhost:5173)

### 3. Run **counter-v2**

```bash
cd counter-v2
npm install
npm run dev
```

The application will be available at: [http://localhost:5173](http://localhost:5173) (port may vary)

---

## Technologies Used

### Common for both projects:

* **React** – library for building user interfaces
* **TypeScript** – strong typing
* **Vite** – tool for fast project setup and bundling

### Additionally in **counter-v1**:

* **Redux Toolkit** – modern approach to state management
* **React-Redux** – integration of Redux with React

---

* **counter-v1**

![main-page](images/main.png)
![settings-page](images/setting.png)

* **counter-v2**

![main-v2-page](images/main-v2.png)

