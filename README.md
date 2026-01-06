# 🚀 Demo Vue.js Project

A **production-ready Vue 3 application** built with **Vite**, **TypeScript**, **ESLint**, **Prettier**, and **Husky**.
This project enforces **strict code quality**, **type safety**, and **pre-commit / pre-push checks** to ensure reliable deployments.

---

## 📦 Tech Stack

* **Vue 3**
* **Vite**
* **TypeScript**
* **ESLint (strict, no warnings allowed)**
* **Prettier**
* **Husky (Git hooks)**
* **lint-staged**
* **Rollup Visualizer**

---

## 📁 Project Setup

### Install dependencies

```bash
npm install
```

---

## 🧑‍💻 Development

### Start development server

```bash
npm run dev
```

App runs at:

```
http://localhost:5173
```

---

## 🏗 Build

### Production build

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

---

## 🧹 Code Quality

### Lint (no warnings allowed)

```bash
npm run lint
```

### Auto-fix lint issues

```bash
npm run lint:fix
```

### Format code

```bash
npm run format
```

---

## 🧪 Tests & Health Check

### Run full production health check

```bash
npm run health
```

This command verifies:

* ✅ ESLint (errors + warnings)
* ✅ TypeScript type safety
* ✅ Successful production build

### Run tests

```bash
npm test
```

> `npm test` is mapped to the **production health check**.

---

## 🔐 Git Hooks (Husky)

### Pre-commit

* Runs ESLint (strict)
* Blocks commit on any error or warning

### Pre-push

* Runs full production health check
* Blocks push if app is not production-ready

---

## 📊 Bundle Analysis

After running:

```bash
npm run build
```

Open:

```
dist/stats.html
```

This shows:

* Bundle size
* Dependency breakdown
* Gzip / Brotli sizes

Useful before production deploys.

---

## 🌍 Environment Variables

Create a `.env` file:

```env
VITE_API_URL=https://api.example.com
```

Example file:

```
.env.example
```

> Environment variables are **type-safe** and validated at build time.

---

## 📂 Recommended Project Structure

```
src/
├── assets/
├── components/
├── views/
├── router/
├── stores/
├── types/
├── App.vue
└── main.ts
```

---

## ✅ Production Standards Enforced

* No ESLint warnings allowed
* Strict TypeScript configuration
* Modular file & function size limits
* Pre-commit & pre-push protection
* CI-ready scripts
* Cross-platform compatible

---

## 🚀 Deployment Checklist

Before deploying:

```bash
npm run health
```

If it passes → **safe to deploy** ✅

---

## 📜 License

Private project – internal use only.

---

## 🙌 Author
Dileep Kushwaha
📧 Email: dileepkushwaha8090@gmail.com

Built with ❤️ using modern Vue best practices.
