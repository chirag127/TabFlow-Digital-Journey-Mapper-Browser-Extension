---
name: "🚀 Feature Request or Bug Fix"
about: "Propose a new feature, improvement, or report a bug."
title: ""
labels:
  - "enhancement"
  - "bug"
  - "feature"
assignees:
  - "chirag127"
---

## 🚀 Pull Request Title

_Please use Conventional Commits for your PR title. Examples:_
*   `feat: Add new graph visualization option`
*   `fix: Resolve navigation tracking edge case`
*   `refactor: Optimize data processing pipeline`
*   `docs: Update installation guide`

## 📝 Description

### What does this PR do?

_Provide a clear and concise description of the changes introduced by this pull request. Explain the problem it solves, the new functionality it adds, or the improvements it brings._

### How was it solved?

_Detail the technical approach taken. Highlight any specific architectural decisions, algorithms, or design patterns utilized. Mention trade-offs or alternatives considered._

### Why was this solution chosen?

_Justify the chosen solution. Reference relevant architectural principles (e.g., SOLID, DRY, KISS) or performance considerations._

## 🔗 Related Issues

_Link any relevant GitHub issues that this PR addresses, e.g., `Closes #123`, `Fixes #456`, `Resolves #789`._

## 💡 Type of Change

_Please check the boxes that apply._

- [ ] **Feature**: New functionality, non-breaking change.
- [ ] **Bug Fix**: Fixes an existing issue, non-breaking change.
- [ ] **Refactor**: Code restructuring without changing external behavior.
- [ ] **Documentation**: Updates to README, Wiki, or inline comments.
- [ ] **Performance**: Code optimization to improve speed or resource usage.
- [ ] **Security**: Fixes a vulnerability or improves security measures.
- [ ] **Chore**: Maintenance, build process, or tooling changes.

## ✅ Checklist for Reviewers & Authors

_Please ensure all the following points are addressed before requesting a review or merging this PR._

### **Code Quality & Standards**
- [ ] Code adheres to the project's coding style guidelines (e.g., consistent indentation, naming conventions).
- [ ] Follows **SOLID**, **DRY**, and **KISS** principles.
- [ ] Uses clear, semantic naming for variables, functions, and classes.
- [ ] Guard clauses are used for early exits, reducing nesting.
- [ ] Code is self-documenting; comments are used only to explain *why*, not *what*.

### **Testing & Verification**
- [ ] New code is covered by **unit tests** (`tests/unit/`).
- [ ] **Integration tests** (`tests/integration/`) are added if relevant for component interaction.
- [ ] **E2E tests** (`tests/e2e/`) are updated/added for critical user flows, especially for UI changes.
- [ ] All tests pass without errors (`npm test`).
- [ ] Code coverage is maintained or improved (aim for 100% branch coverage).
- [ ] The feature/fix has been manually tested in target browsers (Chrome, Firefox, Edge, etc.).

### **Documentation**
- [ ] README.md has been updated if there are changes to setup, usage, or core features.
- [ ] Relevant inline documentation/JSDoc comments are added for complex functions or new APIs.
- [ ] Any new configuration options are documented.

### **Browser Extension Specifics**
- [ ] Manifest file (`manifest.json`) is correctly updated for any new permissions or content scripts.
- [ ] Performance impact on browser and active tabs has been considered and minimized.
- [ ] Privacy implications have been reviewed; data handling is secure and transparent.
- [ ] Memory usage is optimized; no significant leaks detected.

### **Security & Performance**
- [ ] Inputs are sanitized to prevent common vulnerabilities (e.g., XSS, injection).
- [ ] Sensitive data is handled securely (if applicable).
- [ ] No new performance bottlenecks introduced (checked via browser dev tools).
- [ ] Follows Green Software principles: efficient algorithms, lazy loading where appropriate.

### **User Experience (UI/UX) - if applicable**
- [ ] UI changes align with the existing design system (Liquid Glass + Neo-Brutalist + Material You 3.0).
- [ ] UI is responsive and accessible.
- [ ] Animations and micro-interactions are fluid and enhance user experience.
- [ ] INP (Interaction to Next Paint) has been considered and optimized (< 200ms).

## 🧪 How to Test (for Reviewers)

_Please provide detailed steps for reviewers to easily test and verify the changes in this PR._

1.  `git clone https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension.git`
2.  `cd TabFlow-Digital-Journey-Mapper-Browser-Extension`
3.  `npm install` (or `pnpm install`, `yarn install` if preferred)
4.  `npm run build`
5.  Load the `dist/` folder as an unpacked extension in your browser.
6.  _Specific testing steps related to this PR_:
    *   ... (e.g., "Navigate to X, click Y, observe Z")
    *   ...

## 📦 Deployment Notes

_Are there any special instructions or considerations for deploying this change (e.g., database migrations, environment variables, external service configuration)?_

## 🏁 Definition of Done

- [ ] All CI/CD checks pass.
- [ ] Code has been reviewed and approved by at least one maintainer.
- [ ] All necessary documentation (code, user) is updated.
- [ ] Performance and security checks are satisfactory.
- [ ] This PR is ready for merge.