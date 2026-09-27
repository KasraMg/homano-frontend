# Homano Frontend

Frontend application for **Homano**, a modern e-commerce platform built with **React**, **TypeScript**, and **Vite**.

The application provides a complete shopping experience including product browsing, authentication, cart management, order management, content pages, location-based features, and responsive UI.

## 🚀 Features

* 🔐 User authentication
* 👤 User profile management
* 🛍️ Product browsing and management
* 🔎 Product search and filtering
* 🛒 Shopping cart
* 📦 Order management
* 📍 Location and map integration
* 📅 Persian date picker
* ⭐ Product ratings
* 🎠 Responsive carousels
* 🔔 Toast notifications
* 📱 Responsive design
* ⚡ Server state management with TanStack Query
* 🗃️ Client state management with Zustand
* 🎨 Modern UI with Tailwind CSS

## 🛠️ Tech Stack

* **React 19**
* **TypeScript**
* **Vite**
* **React Router**
* **TanStack Query**
* **Zustand**
* **Tailwind CSS**
* **React Hook Form**
* **Yup**
* **Leaflet**
* **React Leaflet**
* **Embla Carousel**
* **Lucide React**
* **React Icons**
* **Shadcn UI**
* **Sonner**
* **JavaScript Cookie**

## 📂 Project Structure

The project follows a modular frontend structure:

```text
src/
├── components/
├── features/
├── hooks/
├── layouts/
├── pages/
├── routes/
├── services/
├── store/
├── types/
└── ...
```

The application separates UI components, features, API communication, state management, routing, and reusable logic to keep the codebase maintainable and scalable.

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/KasraMg/homano-frontend.git

cd homano-frontend
```

Install dependencies:

```bash
npm install
```

## 🔐 Environment Variables

Create a `.env` file in the project root:

```env
VITE_LOCAL_BACKEND_URL=http://localhost:1000/api
VITE_LOCAL_ASSETS_URL=http://localhost:1000
```

For the deployed backend:

```env
VITE_LOCAL_BACKEND_URL=https://homano-backend.vercel.app/api
VITE_LOCAL_ASSETS_URL=https://homano-backend.vercel.app
```

These variables are used to configure the backend API and asset URLs.

## ▶️ Running the Application

Start the development server:

```bash
npm run dev
```

Vite will start the development server and provide the local URL in the terminal.

## 🏗️ Build

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## 🧹 Linting

Run ESLint:

```bash
npm run lint
```

## 🔌 Backend

The frontend communicates with the Homano backend through a REST API.

**Backend repository:**

https://github.com/KasraMg/homano-backend

**Production API:**

```text
https://homano-backend.vercel.app/api
```

## 🌐 Live Demo

[Homano](https://homano.vercel.app/)

## 🔗 Related Projects

* **Frontend:** https://homano.vercel.app/
* **Backend:** https://homano-backend.vercel.app/

## 👨‍💻 Author

**Kasra Mg**

[GitHub](https://github.com/KasraMg)
