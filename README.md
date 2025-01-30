# Habits Tracker

## 📌 Descrição
Habits Tracker é uma aplicação full-stack desenvolvida para ajudar usuários a monitorar e manter seus hábitos de forma eficiente. Com uma interface responsiva e amigável, permite o registro de hábitos diários, acompanhamento de progresso e visualização de estatísticas.

## 🚀 Tecnologias Utilizadas
### 🔹 Frontend
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)

### 🔹 Backend
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Prisma ORM](https://www.prisma.io/)
- [SQLite/PostgreSQL](https://www.postgresql.org/)

## 🛠️ Como Executar o Projeto

### 🔹 Pré-requisitos
- **Node.js** instalado ([Baixar aqui](https://nodejs.org/))
- **Gerenciador de pacotes npm ou yarn**

### 🔹 Passo a Passo

#### 1️⃣ Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/habits-tracker.git
cd habits-tracker
```

#### 2️⃣ Configurar o Backend
```sh
cd backend
npm install # ou yarn install
```

- Criar o banco de dados:
```sh
npx prisma migrate dev --name init
```

- Iniciar o servidor:
```sh
npm run dev # ou yarn dev
```

#### 3️⃣ Configurar o Frontend
```sh
cd ../frontend
npm install # ou yarn install
```

- Iniciar o servidor frontend:
```sh
npm run dev # ou yarn dev
```

A aplicação estará disponível em **http://localhost:5173/** (ou outra porta definida no Vite).

## 📷 Capturas de Tela
_(Adicione aqui algumas screenshots da aplicação em funcionamento.)_

## 📌 Funcionalidades
✅ Registro e edição de hábitos
✅ Visualização de progresso
✅ Interface responsiva e moderna
✅ Integração com banco de dados

## 🛠 Melhorias Futuras
- Implementação de autenticação JWT
- Notificações para lembretes de hábitos
- Exportação de dados para relatórios

## 📄 Licença
Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE.

---
Desenvolvido com 💙 por Luis Felipe Capel(https://github.com/CapelLuisFelipe/)

