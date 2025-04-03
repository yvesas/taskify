# Taskify

Is a micro-SaaS for freelancers and small teams to manage tasks. It allows you to create, edit, delete, and view tasks, with basic authentication.
with Nest.js, Prisma, PostgreSQL, React.js, TailwindCSS, ShadcnUI, Docker, Typescript.

---

## Project Structure

- docker-compose.yml: Service orchestration configuration
- Submodule git taskify-frontend: [Taskify-backend](https://github.com/yvesas/taskify-backend)
- Submodule git taskify-backend: [Taskify-frontend](https://github.com/yvesas/taskify-frontend)

---

## Prerequisites

Before you begin, make sure you have installed:

[Docker and Docker Compose](https://docs.docker.com/get-docker/)

## **🚀 Running the Application**

#### 1. Clone the main repository WITH the submodules

```
git clone --recursive https://github.com/yvesas/hidoctor-backend.git
```

The `--recursive` parameter already automatically downloads the submodules (frontend and backend).


#### 2. If you have already cloned without submodules

Run inside the project folder:

```
git submodule update --init --recursive
```
#### 3. Finally start Docker

```
 docker compose up --build
```

---

## 🏁 Accessing the application

The application will be available at:

Frontend: [`http://localhost:5173`](http://localhost:5173)

Backend - API: [`http://localhost:3000`](http://localhost:3000)

---

<div data-badges style="display: flex; gap: 10px;">
    <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
    <img src="https://img.shields.io/badge/prisma-%232D3748.svg?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
    <img src="https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
    <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
    <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcn/ui&logoColor=white" alt="Shadcn/ui" />  
    <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> 
    <img src="https://img.shields.io/badge/docker-257bd6?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>
