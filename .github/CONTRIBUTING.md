# 🚀 Contributing to TabFlow-Navigation-Path-Analytics-Browser-Extension

Thank you for considering contributing to TabFlow! We appreciate your interest in helping to improve this advanced browser extension for navigation path analytics.

This project adheres to the **Apex Technical Authority** standards, focusing on Zero-Defect, High-Velocity, and Future-Proof development. We expect all contributions to align with these principles and the established architectural patterns.

## 💡 Core Principles

*   **Code Quality:** Aim for readable, maintainable, and well-tested code. Adhere to SOLID, DRY, and KISS principles.
*   **Modularity:** Contributions should align with the existing modular architecture. New features should be self-contained.
*   **Performance:** Optimize for speed and efficiency. Browser extensions have resource constraints.
*   **Security:** Implement robust input validation and sanitization. Follow the DevSecOps protocol.
*   **Documentation:** All significant code changes, new features, or bug fixes must be accompanied by updated documentation, especially within the `README.md` and relevant code comments (explaining the *why*, not the *what*).

## 🛠️ Getting Started

1.  **Fork the Repository:** Create your own fork of the `TabFlow-Navigation-Path-Analytics-Browser-Extension` repository.
2.  **Clone Your Fork:** `git clone git@github.com:<your-username>/TabFlow-Navigation-Path-Analytics-Browser-Extension.git`
3.  **Set Up Development Environment:** Follow the setup instructions in the `README.md` to install dependencies and set up the build process.
    *   **Note:** This project uses **TypeScript 6.x**, **Vite 7**, **WXT** for browser extensions, and is linted/formatted by **Biome**. Testing is handled by **Vitest** and **Playwright**.
4.  **Create a Feature Branch:** `git checkout -b feature/your-feature-name` or `git checkout -b fix/bug-description`

## ✅ Contribution Workflow

1.  **Make Your Changes:** Implement your feature or fix the bug.
2.  **Write Tests:** Ensure your changes are covered by unit tests (`*.test.ts`) and, if applicable, end-to-end tests.
3.  **Lint and Format:** Run `biome check --apply` to ensure code quality and formatting standards are met.
4.  **Test Your Changes:** Execute `vitest` to run unit tests and `npx playwright test` for E2E tests. Ensure all tests pass and there are no console errors.
5.  **Commit Your Changes:** Use **Conventional Commits** for your messages (e.g., `feat: add user-defined theme settings`, `fix: correct data visualization rendering bug`).
    ```bash
    git add .
    git commit -m "feat: implement new analytics export format"
    ```
6.  **Push to Your Fork:** `git push origin feature/your-feature-name`
7.  **Open a Pull Request:** Create a new Pull Request from your fork to the main `TabFlow-Navigation-Path-Analytics-Browser-Extension` repository.
    *   Ensure the PR title follows the Conventional Commits format.
    *   Provide a clear and concise description of your changes.
    *   Link to any relevant issues.

## 📝 Issue Tracking

*   **Bugs:** Please report bugs using the **Bug Report Issue Template**. Provide detailed steps to reproduce, expected behavior, and actual behavior.
*   **Feature Requests:** Suggest new features via the **Feature Request Issue Template** (if available, otherwise open a new issue with the `enhancement` label).

## ⚖️ License

By contributing to this project, you agree that your contributions will be licensed under the **CC BY-NC 4.0 License**.

## 🤝 Community & Support

If you have questions or need clarification, please open an issue. We strive to foster a collaborative and supportive environment.

**Let's build the best navigation analytics extension together!**

**Star ⭐ this Repo** to show your support and stay updated!