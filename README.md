# To-Do List App (MERN Stack)

Это полнофункциональное приложение для управления задачами, созданное с использованием **MERN-стека**:
**MongoDB + Express + React + Node.js**

Позволяет добавлять, редактировать, фильтровать, выполнять и удалять задачи.
Frontend задеплоен на GitHub Pages.

---

## Скриншоты

![Главный экран](./main-screen.png)

---

## 🔗 Демо

🟢 [Открыть приложение (GitHub Pages)](https://AleksandrRDK.github.io/to-do_client)

---

## 📌 Функционал

-   ✅ Добавление, удаление и редактирование задач
-   🔄 Отметка задач как выполненных / невыполненных
-   🔍 Фильтрация по категории и статусу
-   🌍 Получение и отправка данных через собственный backend (`/api/tasks`)
-   🧠 Использование RTK Query для работы с API
-   ✨ Анимации с `react-transition-group`
-   🎨 Стилизация с использованием SCSS

---

## ⚙️ Используемые технологии

### 🔹 Фронтенд (`/client`)

-   React 18
-   Redux Toolkit + RTK Query
-   React Bootstrap, React Icons
-   React Transition Group
-   SASS / SCSS
-   GitHub Pages (деплой)

### 🔹 Бэкенд (`/server`)

-   Node.js + Express
-   MongoDB Atlas + Mongoose
-   dotenv, CORS
-   Nodemon (dev)

---

## 🚀 Установка и запуск

### 1. Клонировать репозиторий:

```
git clone https://github.com/AleksandrRDK/to-do_list.git
cd to-do_list
```

### 2. Установить зависимости для клиента:

```
cd client
npm install
npm start
```

### 3. Установить зависимости и запустить сервер:

```
cd server
npm install
npm run dev
```

📌 Убедитесь, что в `server/.env` указан корректный `MONGO_URI`.

---

🌐 Подключение к backend-серверу
Во время разработки приложение использует локальный сервер по адресу:

const baseUrl = 'http://localhost:5000/api';

---

## 🛠 Планы по улучшению

-   🔐 Добавить авторизацию пользователей
-   📅 Подключить уведомления и напоминания
-   ☁️ Задеплоить backend в облако (например, Render / Railway)

---

## 👨‍💻 Автор

**Александр Рудаков**
📧 [aleksandrrdk.code@gmail.com](mailto:aleksandrrdk.code@gmail.com)
📂 [GitHub: AleksandrRDK](https://github.com/AleksandrRDK)
