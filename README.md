# BudgetBuddy

## Instalação do Projeto

### Pré-requisitos

Certifique-se de ter instalado os seguintes softwares em sua máquina:

- Node.js (versão 12.0 ou superior)
- Yarn (gerenciador de pacotes)

### Passos para Instalação

#### Clonar o Repositório do Projeto

1. **Clone o repositório do projeto**:

    ```bash
    git clone https://github.com/MatheusBeneti/BudgetBuddy.git
    cd budgetbuddy
    ```

#### Instalação do Frontend

2. **Navegue até a pasta `frontend` e instale as dependências**:

    ```bash
    cd frontend
    yarn install
    ```

3. **Inicie o servidor de desenvolvimento do frontend**:

    ```bash
    yarn dev
    ```

    O servidor do frontend será iniciado em [http://localhost:3000](http://localhost:3000).

#### Instalação do Backend

4. **Navegue até a pasta `backend` e instale as dependências**:

    ```bash
    cd ../backend
    yarn install
    ```

5. **Inicie o servidor de desenvolvimento do backend**:

    ```bash
    yarn start
    ```

    O servidor do backend será iniciado em [http://localhost:3001](http://localhost:3001).

### Estrutura do Projeto

#### Frontend

A estrutura do diretório `frontend` é a seguinte:

```
frontend/
├── node_modules/
├── public/
├── src/
│ └── app/
│ ├── favicon.ico
│ ├── globals.css
│ ├── layout.tsx
│ └── page.tsx
├── .eslintrc.json
├── .gitignore
├── next-env.d.ts
├── next.config.mjs
├── package.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.js
└── tsconfig.json
```

#### Backend

A estrutura do diretório `backend` é a seguinte:

```
backend/
├── node_modules/
├── src/
│ ├── app.module.ts # Módulo raiz do NestJS
│ ├── main.ts # Ponto de entrada do NestJS
│ ├── api/ # APIs Next.js (se necessário para SSR ou SSG)
│ ├── config/ # Configurações do projeto (banco de dados, etc.)
│ ├── users/
│ │ ├── dto/ # Data Transfer Objects para a entidade User
│ │ ├── entities/ # Entidades do banco de dados (User)
│ │ ├── users.controller.ts # Controlador para as rotas de usuários
│ │ ├── users.module.ts # Módulo NestJS para a feature de usuários
│ │ └── users.service.ts # Serviços para lógica de negócios de usuários
│ ├── common/ # Módulos, interceptadores, filtros, etc., comuns
│ └── test/ # Testes (unitários, e2e)
├── .gitignore
├── package.json # Dependências do projeto e scripts
├── tsconfig.json # Configurações do TypeScript
└── nest-cli.json # Configurações do CLI do NestJS
```

### Créditos

- Beneti
- Kayo
- Manzato
- Tiago
