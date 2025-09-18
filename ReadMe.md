# LiquidApi

**LiquidApi** is a lightweight Composer project creator for building fast, modular, and modern PHP APIs.  
It provides a clean, extensible skeleton that helps you start coding immediately without the usual boilerplate overhead.

---

## ✨ Features

- ⚡ **Slim API skeleton** — minimal and fast, ready for async/event-driven workloads.  
- 🔌 **Plug-and-play architecture** — integrates easily with Symfony components, ReactPHP, or your own libraries.  
- 🧩 **Extensible by design** — add custom bundles or drop-in modules without losing flexibility.  
- 🛠️ **Developer-friendly tooling** — ships with sensible defaults, DTO-first design, and ready-to-use configs.  

---

## ❓ Why LiquidApi?

Modern PHP developers often face a tradeoff:  
- Full-stack frameworks like Symfony or Laravel are powerful but heavy and opinionated.  
- Lightweight micro-frameworks are fast but often lack structure or conventions.  

**LiquidApi bridges the gap** by offering:  
- A **fast, clean starting point** for APIs without framework bloat.  
- **Flexibility** to scale from a simple microservice to a distributed system.  
- **Control** over your stack — use only the components you actually need.  

Whether you’re experimenting, prototyping, or building production-ready services, LiquidApi gives you the freedom to move fast without being boxed in.

---

## 🚀 Getting Started

Create a new project using Composer:

```bash
composer composer create-project liquidrazor/liquid-api my-api
```

or if you are using docker (and like less clutter on your own computer)

```bash
docker run --rm --interactive --tty -u $(id -u):$(id -g) --volume $PWD:/app composer create-project liquidrazor/liquid-api my-api
```

---

## 📂 Project Structure

```bash
my-api/
├── config/          # Configuration files
├── public/          # Public entrypoint (index.php)
├── src/             # Your application source code
├── tests/           # Unit and integration tests
└── composer.json    # Project dependencies

```
---

## 🧩 Extending LiquidApi

LiquidApi is built to be extensible:

- Add Symfony components as needed.
- Swap in ReactPHP for async APIs.
- Write and share your own bundles.

---

## 🛠️ Requirements

- PHP 8.3+
- Composer 2.0+

---

## 📖 License

LiquidApi is open-sourced under the MIT license
