# React Jobs

A job listings application built with React. This project was developed by following Traversy Media's [React Crash Course 2024](https://www.youtube.com/watch?v=LDB4uaJ87e0) tutorial on YouTube.

## 📌 About the Project

This is a job listing application built to practice the core concepts of React, including components, props, state, hooks, routing, and data fetching. Users can browse job listings, view job details, add new job postings, and delete existing ones.


## 🚀 Tech Stack

- **React 19** – UI library
- **Vite** – Fast development environment and build tool
- **React Router DOM** – Client-side routing
- **Tailwind CSS** – Styling
- **React Icons** – Icon library
- **React Toastify** – Toast notifications
- **React Spinners** – Loading spinners
- **JSON Server** – Mock REST API / backend

## ✨ Features

- Home page and job listings page
- Job listings displayed as cards
- Single job detail page
- Add new job form
- Delete job functionality
- Page navigation and active link highlighting with React Router
- Custom 404 page
- Loading spinner while fetching data

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Ardaozk54/React-Jobs.git
cd React-Jobs
```

Install dependencies:

```bash
npm install
```

## ▶️ Running the App

You need **two separate terminals** to run this project: one for the frontend and one for the mock API (JSON Server).

**Terminal 1 – Frontend (Vite dev server):**

```bash
npm run dev
```

**Terminal 2 – Backend (JSON Server):**

```bash
npm run server
```

This serves the `src/jobs.json` file as an API at `http://localhost:8000`.

The app will be available by default at `http://localhost:5173`.

## 📦 Build

To build the project for production:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## 🎥 Reference Video

This project was built by following this YouTube tutorial:

[React Crash Course 2024 - Traversy Media](https://www.youtube.com/watch?v=LDB4uaJ87e0)

## 👤 Author

[Ardaozk54](https://github.com/Ardaozk54)