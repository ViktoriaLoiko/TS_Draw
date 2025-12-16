# 📄 README.md (English + Русский)

> This README file contains **two languages: English and Russian**.
> Этот файл README содержит **два языка: Английский и Русский**.

---

# 🎨 Drawing App — Web-based Paint-like Application

# 🎨 Drawing App — Веб-приложение, похожее на Paint

---

🖼️ Screenshot/Скриншот


---

## 🇬🇧 **English Version**

### 📌 Overview

A simple **web-based drawing application inspired by Microsoft Paint**, built with **HTML, CSS, TypeScript**, and **Node.js (Express)**.
Users can draw on a canvas, choose colors, change brush size, save drawings to a gallery, and delete them individually or all at once.

### ✨ Features

* 🎨 Canvas drawing with adjustable brush size
* 🌈 Color palette + custom color picker
* 💾 Save drawings to a local gallery
* 🗂️ View all saved images
* ❌ Delete a single image or remove all images
* 🧹 Clean, responsive layout /Clear canvas (New File button)

### 📦 Technologies Used

* **TypeScript**
* **HTML5 Canvas**
* **CSS3**
* **Node.js (Express)**
* **File system (fs)** for saving images

### 📦 Installation & 🚀 Running

```bash
git clone https://github.com/ViktoriaLoiko/TS_Draw.git
cd TS_Draw 
npm install
npm run build
npm start
```

Then open:
👉 [http://localhost:3000](http://localhost:3000)

### 📁 Project Structure

```
 TS_2/
├── node_modules/        # Installed dependencies (ignored by Git)
├── public/              # Client-side files (served statically)
│   ├── css/
│   │   └── style.css    # Application styles
│   ├── img/             # Saved drawings (PNG images)
│   ├── js/
│   │   ├── app.js       # Compiled frontend JavaScript
│   │   └── server.js    # Compiled backend JavaScript
│   └── index.html       # Main HTML file
├── src/                 # TypeScript source files
│   ├── app.ts           # Frontend logic (Canvas drawing)
│   └── server.ts        # Express server logic
├── .gitignore           # Git ignore rules
├── package.json         # Project configuration and scripts
├── package-lock.json    # Dependency lock file
├── tsconfig.json        # TypeScript configuration
└── README.md            # Project documentation
```

---

## 🇷🇺 **Русская версия**

### 📌 Описание

Простое **веб-приложение для рисования, похожее на Microsoft Paint**, созданное с использованием **HTML, CSS, TypeScript** и **Node.js (Express)**.
Пользователь может рисовать, выбирать цвета, менять размер кисти, сохранять рисунки в галерею и удалять их по одному или все сразу.

### ✨ Возможности

* Рисование на холсте + настройка размера кисти
* Палитра цветов + выбор собственного цвета
* Сохранение рисунков в локальную галерею
* Удаление одного изображения или всех сразу
* Чистый, удобный интерфейс

### 📦 Используемые технологии

* **TypeScript**
* **HTML5 Canvas**
* **CSS3**
* **Node.js (Express)**
* **fs** для сохранения изображений

### 🚀 Установка и запуск

```bash
git clone https://github.com/ViktoriaLoiko/TS_Draw.git
cd TS_Draw 
npm install
npm run build
npm start
```

Открыть в браузере:
👉 [http://localhost:3000](http://localhost:3000)

### 📁 Структура проекта

```
TS_2/
├── node_modules/        # Установленные зависимости (игнорируются Git)
├── public/              # Клиентская часть (отдаётся сервером)
│   ├── css/
│   │   └── style.css    # Стили приложения
│   ├── img/             # Сохранённые рисунки (PNG)
│   ├── js/
│   │   ├── app.js       # Скомпилированный frontend JavaScript
│   │   └── server.js    # Скомпилированный backend JavaScript
│   └── index.html       # Главная HTML-страница
├── src/                 # Исходные файлы TypeScript
│   ├── app.ts           # Логика рисования (Canvas)
│   └── server.ts        # Сервер Express
├── .gitignore           # Правила игнорирования Git
├── package.json         # Конфигурация проекта и скрипты
├── package-lock.json    # Фиксация версий зависимостей
├── tsconfig.json        # Конфигурация TypeScript
└── README.md            # Документация проекта

```

---
