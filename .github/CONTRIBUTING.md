# Contributing to TabFlow Digital Journey Mapper

Thank you for considering contributing to `TabFlow-Digital-Journey-Mapper-Browser-Extension`! As an Apex-standard project, we uphold rigorous standards for code quality, architectural integrity, and developer experience. We operate on the principle of "Zero-Defect, High-Velocity, Future-Proof."

## 1. Governance and Standards

### 1.1 Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We maintain a professional, respectful, and high-performance development environment.

### 1.2 Architectural Principles
We adhere strictly to the following principles for browser extension development:

*   **Feature-Sliced Design (FSD):** Codebase structure is organized by feature layers (shared, entities, features, widgets, pages, app) to ensure scalability and clear boundaries.
*   **SOLID & DRY:** Code must be modular, reusable, and maintainable. Avoid unnecessary duplication.
*   **High TypeScript Strictness:** All new code must be written in TypeScript and pass strict checks. Avoid reliance on `any`.
*   **API Integrity:** Browser API interactions must be robustly handled, especially for persistence (IndexedDB, Storage API) and permissions.

## 2. Setting Up the Development Environment

`TabFlow` is built using **WXT (Web Extension Toolkit)**, **Vite**, and **TypeScript**, targeting performance and cross-browser compatibility.

### Prerequisites

1.  **Node.js:** v20.x or higher (LTS recommended).
2.  **uv:** Highly recommended for ultra-fast, secure dependency management. (Optional fallback: `npm`)
3.  **Git:** Latest version.

### Installation

bash
# 1. Clone the repository
git clone https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension.git
cd TabFlow-Digital-Journey-Mapper-Browser-Extension

# 2. Install dependencies using uv (or npm if uv is unavailable)
uv sync

# 3. Start the development server (WXT handles hot reloading and build)
npm run dev


The extension will be built into the `dist` directory, ready for manual loading into your development browser (e.g., Chrome's `chrome://extensions/` or Firefox's `about:debugging#/runtime/this-firefox`).

## 3. Standard Workflow

We utilize the standard GitHub Flow for contributions:

1.  **Fork** the repository: `https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension`.
2.  **Clone** your fork locally.
3.  **Create a feature branch:** `git checkout -b feature/descriptive-summary`.
4.  **Commit:** Use clear, concise commit messages that summarize the change (Conventional Commits style is preferred).
5.  **Push** your branch.
6.  **Open a Pull Request (PR):** Target the `main` branch of the upstream repository.

## 4. Testing and Linting

All contributions **must** pass the continuous integration (CI) pipeline checks. Running these locally is mandatory before submitting a PR.

### 4.1 Linting and Formatting (Biome)

We use **Biome** for ultra-fast, professional formatting and linting standards.

bash
# Check for formatting/linting issues
npm run lint

# Automatically fix most issues (recommended practice)
npm run format


### 4.2 Testing (Vitest & Playwright)

New features require high coverage via unit tests, and bug fixes must include regression tests.

bash
# Run all unit and integration tests (Vitest)
npm run test

# Run End-to-End tests (Playwright) - Use this for critical user journeys
# npm run test:e2e


## 5. Submitting a Pull Request (PR)

All PRs require architectural review and must satisfy the CI checks. Ensure your PR description adheres to the structure defined in the [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md).

### PR Checklist (Mandatory Review Gate)

*   [ ] I have read the Contributing Guidelines and the [Agent Directives (AGENTS.md)](AGENTS.md).
*   [ ] The code adheres to the **Feature-Sliced Design (FSD)** architecture and is logically layered.
*   [ ] My code is compliant with **Strict TypeScript** standards.
*   [ ] All unit tests pass locally (`npm run test`).
*   [ ] The code has been formatted and linted using `npm run format`.
*   [ ] Functionality is verified across the target browsers (Chrome/Firefox).
*   [ ] Documentation (internal comments, API docs, or README updates) has been added/updated as necessary.
*   [ ] The pull request references any related issues (e.g., `Fixes #123`, `Relates to #456`).
