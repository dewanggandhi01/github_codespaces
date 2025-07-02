# github_codespaces

> ⚠️ **Note:** This repository is created for learning and experimenting with GitHub Codespaces. It is not intended to be a production-ready project.

This repository serves as a quick guide and reference for getting started with **GitHub Codespaces** — a cloud-hosted development environment built right into GitHub.

---

## 🚀 What is GitHub Codespaces?

GitHub Codespaces lets you code from anywhere using a cloud-based environment. It offers a consistent development setup with support for Visual Studio Code, GitHub CLI, and more — right from your browser or local editor.

---

## ✅ Why Codespaces Helps

- 🧩 **Reproducible onboarding** — No more "works on my machine" issues.
- 🌐 **Anywhere access** — Code from a browser, desktop, or tablet.
- ⚡ **Fast experimentation** — Test branches and PRs in isolated environments.

---

## ⚙️ How to Use GitHub Codespaces

### 🔹 From GitHub UI:
1. Go to this repo.
2. Click `Code` → `Codespaces` → `Create codespace on main`.

### 🔹 From VS Code:
1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac).
2. Search and select: `Codespaces: Create New Codespace`.

### 🔹 From GitHub CLI:
```bash
gh auth login
gh codespace create --repo dewanggandhi01/github_codespaces
gh codespace list         # List all codespaces
gh codespace code         # Open in local VS Code
gh codespace ssh          # SSH into the codespace
