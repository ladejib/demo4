# 🎭 Playwright Kubernetes Template (JavaScript Version)

This project is a **ready-to-use Playwright testing framework** designed to run easily inside Kubernetes with Git-sync integration.  
Use this repo to launch scalable, sharded browser tests across clusters.

---

## 🚀 Features
- JavaScript-based Playwright tests
- Sync tests dynamically using Git-Sync sidecar
- Kubernetes Job + Persistent HTML report output
- GitHub Actions CI/CD ready
- Minimal, clean project structure
- Template Repository (click \"Use this template\")

---

## 📂 Project Structure


playwright-k8s-template/ ├── tests/ ├── playwright.config.js ├── entrypoint.sh ├── package.json ├── .github/workflows/ci.yml ├── .gitignore └── README.md


## 📜 Usage (Locally)

1. Install dependencies:
   ```bash
   npm install

npx playwright test


npx playwright show-report
