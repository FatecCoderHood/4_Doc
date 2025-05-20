# 📘 Manual Geral – Instalação e Execução da Aplicação

> **Público-alvo:** todos os perfis de usuário (Admin, Analista, Consultor)

---

## 🔧 Requisitos do Sistema

- **Java 17**
- **Node.js v18+**
- **MongoDB** (local ou via Docker)
- **Docker + Docker Compose** (opcional)
- Navegador moderno (Chrome, Edge, Firefox)

---

## 📁 Estrutura do Projeto

```
4_GeoHood/
├── backend/        → Spring Boot API (Java)
├── frontend/       → Aplicação web (Vue.js + Vite)
├── docs/           → Documentação
├── docker-compose.yml
```

---

## ▶️ Executando o Projeto Localmente

### 📦 1. Clone o repositório

```bash
git clone https://github.com/FatecCoderHood/4_GeoHood.git
cd 4_GeoHood
```

### 🧠 2. Inicie o MongoDB (se não estiver rodando)

Com Docker:

```bash
docker-compose up -d
```

Ou manualmente, caso você tenha MongoDB local.

### 🧪 3. Rodando o Backend (Java + Spring Boot)

```bash
cd backend
./mvnw spring-boot:run
```

A API sobe em `http://localhost:8080`.

### 🌐 4. Rodando o Frontend (Vue.js)

Em outro terminal:

```bash
cd frontend
npm install
npm run dev
```

O front ficará disponível em `http://localhost:5173`.

---

## 🔐 Login de Teste

| Perfil       | Login                     | Senha     |
|--------------|----------------------------|-----------|
| Administrador| admin@geohood.com          | admin123  |
| Consultor    | consultor@geohood.com      | geo123    |
| Analista     | analista@geohood.com       | geo456    |

---

## 🧭 Navegação Geral

- Menu lateral esquerdo com acesso às funcionalidades
- Responsividade: funciona em desktop e tablets
- Mapas com LeafletJS
