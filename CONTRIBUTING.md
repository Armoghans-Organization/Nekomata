# 🤝 Contributing to Nekomata

Thanks for your interest in contributing to **Nekomata** — a cozy Catppuccin-styled Hugo theme with anime vibes!  
We welcome contributions of all kinds: bug fixes, documentation improvements, new features, and ideas.

---

## 📚 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
  - [Reporting Bugs](#-reporting-bugs)
  - [Suggesting Enhancements](#-suggesting-enhancements)
  - [Pull Requests](#-pull-requests)
- [Development Setup](#-development-setup)
  - [Requirements](#requirements)
- [Commit Guidelines](#-commit-guidelines)
- [Style Guide](#-style-guide)
- [Commit Checklist](#-commit-checklist)
- [Questions?](#-questions)

---

## 📜 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).  
By participating, you are expected to uphold this code.

---

## 🐾 How Can I Contribute?

### 🐛 Reporting Bugs

- Use the **[Issues](https://github.com/Armoghans-Organization/Nekomata/issues)** tab.
- Clearly describe:
  - **Expected behavior**
  - **Actual behavior**
  - **Steps to reproduce**
  - **Screenshots** (if applicable)

### 🌟 Suggesting Enhancements

- Open an issue with the `enhancement` label.
- Describe the feature, why it would be useful, and how you imagine it working.
- Mockups are always welcome!

### 🛠️ Pull Requests

1. **Fork** the repo and create your branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make your changes:**
   - Stick to the Catppuccin style and anime vibe.
   - Keep commits focused and meaningful.
   - Run Hugo locally to test:
     ```bash
     pnpm dev
     ```
3. **Commit with a clear message:**
   ```bash
   git commit -m "feat: add cute navbar with Catppuccin styling"
   ```
4. **Push to your fork:**
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a PR** against the main branch.

---

## 📦 Development Setup

### Requirements

| Tool    | Version      |
|---------|--------------|
| Node.js | >= 20        |
| pnpm    | >= 10.15.0   |
| Hugo    | >= 0.148.2   |

**Install dependencies:**
```bash
pnpm install
```

**Run development server:**
```bash
pnpm dev
```

**Production build:**
```bash
pnpm build
```

---

## ✅ Commit Guidelines

We follow **Conventional Commits**:

| Type      | Description                        |
|-----------|------------------------------------|
| feat      | A new feature                      |
| fix       | A bug fix                          |
| docs      | Documentation only changes         |
| style     | Formatting, no code change         |
| refactor  | Code changes, no features/bugs     |
| test      | Adding/updating tests              |
| chore     | Build process or dependency changes|

**Examples:**
```bash
feat: add pastel accent colors
fix: resolve navbar overflow issue
docs: improve README installation guide
```

---

## 🐱 Style Guide

- Stick to Catppuccin color palette 🎨.
- Follow Hugo’s best practices for themes:
  - Use `layouts/partials` for reusable components.
  - Keep `assets/` tidy (CSS/JS/images).
- Write clear, concise documentation for new features.

---

## ✅ Commit Checklist

- [ ] My code builds locally without errors.
- [ ] I wrote or updated tests (if applicable).
- [ ] I updated documentation if needed.
- [ ] My commits use [Conventional Commit messages](https://www.conventionalcommits.org/).

---

## 💌 Questions?

If you’re unsure about anything, open a discussion here:  
👉 [Nekomata Discussions](https://github.com/Armoghans-Organization/Nekomata/discussions)

---

<p align="center">──────── ⋆⋅☆⋅⋆ ────────</p>
<p align="center">
  Made with 🐾 and ☕ by <a href="https://github.com/Armoghans-Organization">Armoghans-Organization</a>
</p>
