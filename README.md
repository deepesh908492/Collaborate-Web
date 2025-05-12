 

````markdown
# Code Sync

A collaborative, real-time code editor that allows users to work together on code in a shared environment.

---

## 🔮 Features

- 💻 Real-time collaboration on code editing across multiple files
- 📁 Create, open, edit, save, delete, and organize files and folders
- 💾 Option to download the entire codebase as a zip file
- 🚀 Unique room generation with room ID for collaboration
- 🌍 Comprehensive language support for versatile programming
- 🌈 Syntax highlighting for various file types with auto-language detection
- 🚀 Code Execution: Users can execute the code directly within the collaboration environment
- ⏱️ Instant updates and synchronization of code changes across all files and folders
- 📣 Notifications for user join and leave events
- 👥 User presence list with online/offline status indicators
- 💬 Real-time group chatting functionality
- 🎩 Real-time tooltip displaying users currently editing
- 💡 Auto suggestion based on programming language
- 🔠 Option to change font size and font family
- 🎨 Multiple themes for personalized coding experience
- 🎨 Collaborative Drawing: Enable users to draw and sketch collaboratively in real-time
- 🤖 Copilot: An AI-powered assistant that generates code, allowing you to insert, copy, or replace content seamlessly within your files.

---

## ⚙️ How to Run the Project

### 🔧 Prerequisites

- Node.js and npm installed
- Git installed (optional but recommended)

---

### 🚀 Manual Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/deepesh908492/Collaborate-Web.git
   cd Collaborate-Web
````

2. **Set environment variables:**

   Create a `.env` file inside both the `client` and `server` directories.

   * **For Client (`client/.env`):**

     ```env
     VITE_BACKEND_URL=http://localhost:3000
     ```

   * **For Server (`server/.env`):**

     ```env
     PORT=3000
     ```

3. **Install dependencies:**

   Run the following commands separately in both `client` and `server` folders:

   ```bash
   npm install
   ```

4. **Start the development servers:**

   * **Client:**

     ```bash
     cd client
     npm run dev
     ```

   * **Server:**

     ```bash
     cd server
     npm run dev
     ```

5. **Access the application:**

   Open your browser and navigate to:

   ```
   http://localhost:5173/
   ```

---

### 🐳 Docker Installation (Optional)

1. **Install Docker**
   [Download Docker Desktop](https://www.docker.com/products/docker-desktop)

2. **Run the containers:**

   ```bash
   docker run -d -p 3000:3000 --name code-sync-server sahilatahar/code-sync-server:latest
   docker run -d -p 5173:5173 --name code-sync-client sahilatahar/code-sync-client:latest
   ```

3. **Access the application:**

   ```
   http://localhost:5173/
   ```

---

## 💻 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge\&logo=typescript\&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge\&logo=react-router\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge\&logo=node.js\&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Socket io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge\&logo=vercel\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)

---

## ✍️ Author

**Deepesh Kumar**

[GitHub](https://github.com/deepesh908492)

```

---

This version of the `README.md` includes only the essentials for running the project, along with your name as the author.

Let me know if you need any further modifications!
```
