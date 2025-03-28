# Taskify

Is a micro-SaaS for freelancers and small teams to manage tasks. It allows you to create, edit, delete, and view tasks, with basic authentication.
with Nest.js, Prisma, PostgreSQL, React.js, TailwindCSS, ShadcnUI, Docker, Typescript.


### Estrutura do Projeto

taskify-frontend/: Código-fonte do frontend React [Taskify-backend](https://github.com/yvesas/taskify-backend)

taskify-backend/: Código-fonte do backend Nest.js [Taskify-frontend](https://github.com/yvesas/taskify-frontend)

docker-compose.yml: Configuração de orquestração de serviços

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

## Pré-requisitos

Docker
Docker Compose

## Iniciando o Projeto

### Clone o repositório:

```
git clone taskify.git
cd taskify
```

```
git clone taskify-backend.git
```

```
git clone taskify-frontend.git
```

## Iniciar todos os serviços:

```
 docker-compose up --build
```

## Serviços

Frontend: http://localhost:5173
Backend: http://localhost:3000
Banco de Dados: PostgreSQL na porta padrão


