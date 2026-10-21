# 🤝 Contributing to Armzi-Studio

Thank you for your interest in contributing to **Armzi-Studio**! We welcome contributions, whether it's reporting a bug, proposing a new feature, or submitting code improvements.

---

## 🧭 Getting Started

1. **Find an Issue:** Browse open issues across our repositories or start a discussion.
2. **Fork the Repository:** Create a personal fork and clone it to your local machine.
3. **Create a Topic Branch:** Create a branch dedicated to your change.
   ```bash
   git checkout -b feat/your-feature-name
   # or
   git checkout -b fix/your-bugfix-name
   ```

---

## 📝 Commit Conventions

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat:` A new feature
- `fix:` A bug fix
- `docs:` Documentation only changes
- `refactor:` A code change that neither fixes a bug nor adds a feature
- `perf:` A code change that improves performance
- `test:` Adding missing tests or correcting existing tests
- `chore:` Changes to build process, tooling, or auxiliary files

*Example:*
```bash
git commit -m "feat(modbus): add CRC-16 check for RTU frame parser"
```

---

## 🛠️ Development & Coding Standards

- **Code Quality:** Ensure your code is properly formatted and passes all project linters (`cargo clippy`, `eslint`, `golangci-lint`, etc.).
- **Tests:** Add unit or integration tests for new functionality, and ensure all existing tests pass before submitting.
- **Documentation:** Update relevant README files, docstrings, or API references when adding or modifying behavior.
- **Keep PRs Focused:** Small, single-purpose pull requests are easier to review and merge quickly.

---

## 🔀 Submitting a Pull Request

1. Push your branch to your fork on GitHub.
2. Open a Pull Request targeting the `main` branch (or specified default branch).
3. Fill out the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) completely.
4. Ensure all CI checks and tests pass.
5. Participate in the code review discussion and make requested adjustments if needed.

Thank you for contributing to open-source and the Armzi-Studio ecosystem! 🚀
