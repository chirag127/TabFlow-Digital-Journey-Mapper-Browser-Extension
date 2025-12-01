<!-- HERO SECTION -->
<p align="center">
  <img src="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/assets/placeholder_hero_banner.png" alt="TabFlow-Digital-Journey-Mapper-Browser-Extension Hero Banner" width="800"/>
</p>

<p align="center">
  <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/actions/workflows/ci.yml">
    <img src="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/actions/workflows/ci.yml/badge.svg" alt="Build Status" style="flat-square">
  </a>
  <a href="https://codecov.io/gh/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/branch/main">
    <img src="https://codecov.io/gh/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/branch/main/graph/badge.svg?token=YOUR_CODECOV_TOKEN_HERE" alt="Code Coverage" style="flat-square">
  </a>
  <img src="https://img.shields.io/badge/Tech_Stack-TS%20%7C%20WXT%20%7C%20Vite%20%7C%20Vue-blue?style=flat-square" alt="Tech Stack">
  <img src="https://img.shields.io/badge/Lint%2FFormat-Biome-important?style=flat-square" alt="Lint/Format">
  <img src="https://img.shields.io/badge/Tests-Vitest%20%7C%20Playwright-success?style=flat-square" alt="Tests">
  <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey?style=flat-square" alt="License">
  </a>
  <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/stargazers">
    <img src="https://img.shields.io/github/stars/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension?style=flat-square&color=yellow" alt="GitHub Stars">
  </a>
</p>

<p align="center">
  ⭐ Star this Repo ⭐
</p>


## Overview

TabFlow is an advanced, privacy-focused browser extension designed to meticulously track and visualize your digital navigation. It transforms raw browsing history into interactive, graph-based journey maps, revealing intricate click paths and referral chains. Gain unparalleled insights into your online exploration patterns, understand digital habits, and optimize your web interactions with this powerful data visualization tool.

## Key Features

*   **Interactive Journey Maps:** Visualize your browsing history as dynamic, graph-based maps.
*   **Path & Referral Tracking:** Clearly see how you navigate between sites and where you come from.
*   **Privacy-First Design:** All data processed and stored locally within your browser.
*   **Detailed Insights:** Understand browsing patterns, identify common routes, and discover inefficiencies.
*   **Developer-Friendly API:** Extend functionality or integrate with other tools (planned).
*   **Cross-Browser Compatibility:** Built with WXT for broad browser support.

## Architecture

This project adheres to the **Feature-Sliced Design (FSD)** methodology, emphasizing strict layer isolation and domain-driven modularity. The core structure organizes code by feature, ensuring scalability and maintainability, particularly for complex browser extension logic.


TabFlow-Digital-Journey-Mapper-Browser-Extension/
├── .github/                  # GitHub Actions, Templates, Security
├── .vscode/                  # VSCode settings
├── public/                   # Static assets
├── src/                      # Core application source code
│   ├── app/                  # Global configuration, routing
│   │   ├── api/              # API definitions for communication
│   │   └── providers/        # Context providers
│   ├── features/             # Business features (e.g., GraphView, DataExport)
│   │   ├── auth/             # (Placeholder) Authentication-related modules
│   │   ├── journey-map/      # Logic for rendering and interacting with journey maps
│   │   └── settings/         # User preferences and configurations
│   ├── entities/             # Data models and fundamental business objects (e.g., `BrowserTab`, `NavigationEvent`)
│   ├── widgets/              # Reusable UI components composed of features/entities
│   │   ├── Header/           # Application header
│   │   └── Sidebar/          # Navigation sidebar
│   ├── pages/                # Specific views for popup, options, or dedicated extension pages
│   │   ├── OptionsPage.vue
│   │   └── PopupPage.vue
│   ├── shared/               # Reusable utilities, UI kit, common types
│   │   ├── ui/               # Design system components
│   │   ├── lib/              # Generic helper functions
│   │   └── types/            # Global TypeScript types
│   ├── background/           # Background service worker script
│   │   └── index.ts
│   ├── content-scripts/      # Scripts injected into web pages
│   │   └── index.ts
│   └── manifest.ts           # WXT browser extension manifest configuration
├── tests/                    # All unit, integration, and E2E tests
│   ├── e2e/                  # Playwright end-to-end tests
│   ├── unit/                 # Vitest unit tests
│   └── setup/                # Test environment setup files
├── .biome.json               # Biome configuration
├── .gitignore                # Git ignored files
├── index.html                # Vite entry point
├── LICENSE                   # Project license
├── package.json              # Project dependencies and scripts
├── pnpm-lock.yaml            # PNPM lockfile
├── PROPOSED_README.md        # This proposed README file
├── README.md                 # Current README file
├── tsconfig.json             # TypeScript configuration
└── vite.config.ts            # Vite build configuration


## Table of Contents

*   [Overview](#overview)
*   [Key Features](#key-features)
*   [Architecture](#architecture)
*   [AI Agent Directives](#ai-agent-directives)
*   [Getting Started](#getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Running Locally](#running-locally)
    *   [Building for Production](#building-for-production)
*   [Development Setup](#development-setup)
    *   [Scripts](#scripts)
    *   [Principles](#principles)
*   [Contributing](#contributing)
*   [License](#license)
*   [Security](#security)
*   [Acknowledgements](#acknowledgements)


## 🤖 AI Agent Directives

<details>
<summary>Click to view AI Agent Directives for TabFlow-Digital-Journey-Mapper-Browser-Extension</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
* **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    * **Context:** User inputs may contain phonetic errors (homophones, typos).
    * **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    * **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
* **MANDATORY MCP INSTRUMENTATION:**
    * **No Guessing:** Do not hallucinate APIs.
    * **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    * **Validation:** Use `docfork` to verify *every* external API signature.
    * **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`package.json`, `Cargo.toml`, `pyproject.toml`) and apply the corresponding **Apex Toolchain**.
* **SCENARIO A: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** **TypeScript 6.x** (Strict), **WXT 0.18+** (Browser Extension Framework), **Vite 7** (Build Tool), **Vue 3** (UI Framework), **Signals** (State Management).
    *   **Lint/Test:** **Biome 1.x** (Linter/Formatter/Bundler), **Vitest 2.x** (Unit Testing), **Playwright 1.x** (E2E Testing).
* **SCENARIO B: SYSTEMS / PERFORMANCE (Rust/Go)**
    * **Stack:** **Rust 1.8x** (Cargo) or **Go 1.2x**.
    * **Lint:** **Clippy** / **GolangCI-Lint**.
* **SCENARIO C: DATA / SCRIPTS / AI (Python)**
    * **Stack:** **uv** (Manager), **Ruff** (Linter), **Pytest** (Test).

---

## 4. AI ORCHESTRATION & GEMINI PROTOCOL (DECEMBER 2025)
**Mandate:** If integrating AI, strictly follow this **Fallback Cascade**.
* **Tier 1 (Intelligence):** `gemini-3-pro` (Stable Dec 2025) - Multimodal Reasoning.
* **Tier 2 (Reasoning):** `gemini-2.5-pro` (Legacy Stable) - Deep analysis/STEM.
* **Tier 3 (Balanced):** `gemini-2.5-flash` - High Volume/Low Latency.
* **Tier 4 (Speed):** `gemini-2.5-flash-lite` - Cost-efficiency.
* **Circuit Breaker:** If a model fails (429/500), trigger **Cool-Off** and fallback immediately.

---

## 5. RECURSIVE PERFECTION LOOP (THE "ZERO-ERROR" MANDATE)
**The Loop:**
1.  **Analyze:** Scan the codebase.
2.  **Fix:** Apply architectural patterns and fixes.
3.  **Lint/Format:** Run the stack's strictest linter (Biome/Ruff).
4.  **Test:** Run the test suite.
5.  **DECISION GATE:**
    * **IF** Errors/Warnings exist -> **GO TO STEP 2** (Self-Correct).
    * **IF** Clean -> **COMMIT** and Present.
**Constraint:** **DO NOT STOP** until the build is perfectly clean.

---

## 6. CORE ARCHITECTURAL PRINCIPLES
*   **SOLID MANDATE:** SRP, OCP, LSP, ISP, DIP.
*   **ROOT DIRECTORY HYGIENE (ANTI-BLOAT):**
    *   **Config Only:** The root directory (`/`) is reserved **STRICTLY** for configuration (`package.json`, `README.md`, `.gitignore`).
    *   **No Root Scripts:** Do not create a `scripts/` folder in the root.
    *   **Containment:** All source code goes to `src/`. All verification code goes to `tests/`.
*   **MODULARITY:** **Feature-Sliced Design (FSD)** for frontend (layers: app, processes, pages, widgets, features, entities, shared), not type.
*   **CQS:** Methods must be **Commands** or **Queries**, never both.
*   **12-Factor App:** Config in environment; backing services attached.

---

## 7. CODE HYGIENE & STANDARDS (READABILITY FIRST)
*   **SEMANTIC NAMING PROTOCOL:**
    *   **Descriptive Verbs:** `calculateWeeklyPay` (Good) vs `calc` (Bad).
    *   **Casing:** `camelCase` (JS/TS), `snake_case` (Python), `PascalCase` (Classes).
*   **CLEAN CODE RULES:**
    *   **Verticality:** Optimize for reading down.
    *   **No Nesting:** Use **Guard Clauses** (`return early`).
    *   **DRY & KISS:** Automate repetitive tasks. Keep logic simple.
    *   **Zero Comments:** Code must be **Self-Documenting**. Use comments *only* for "Why".

---

## 8. RELIABILITY, SECURITY & SUSTAINABILITY
*   **DEVSECOPS PROTOCOL:**
    *   **Zero Trust:** Sanitize **ALL** inputs (OWASP Top 10 2025).
    *   **Supply Chain:** Generate **SBOMs** for all builds.
    *   **Fail Fast:** Throw errors immediately on invalid state.
    *   **Encryption:** Secure sensitive data at rest and in transit.
*   **EXCEPTION HANDLING:**
    *   **Resilience:** App must **NEVER** crash. Wrap critical I/O in `try-catch-finally`.
    *   **Recovery:** Implement retry logic with exponential backoff.
*   **GREEN SOFTWARE:**
    *   **Rule of Least Power:** Choose the lightest tool for the job.
    *   **Efficiency:** Optimize loops ($O(n)$ over $O(n^2)$).
    *   **Lazy Loading:** Load resources only when needed.

---

## 9. COMPREHENSIVE TESTING & VERIFICATION STRATEGY
*   **FOLDER SEPARATION PROTOCOL (STRICT):**
    *   **Production Purity:** The `src/` or `extension/` folder is a **Production-Only Zone**. It must contain **ZERO** test files and **ZERO** test scripts.
    *   **Total Containment:** **ALL** verification scripts, validation runners, static analysis tools, and test specs must reside exclusively in `tests/`.
    *   **Structure:**
        *   `tests/unit/`: Vitest unit tests.
        *   `tests/e2e/`: Playwright E2E tests.
        *   `tests/scripts/`: Verification/Validation scripts (e.g., `verify-imports.js`, `audit-coverage.js`).
*   **TESTING PYRAMID (F.I.R.S.T.):**
    *   **Fast:** Tests run in milliseconds.
    *   **Isolated:** No external dependencies.
    *   **Repeatable:** Deterministic results.
*   **COVERAGE MANDATE:**
    *   **1:1 Mapping:** Every source file **MUST** have a corresponding test file.
    *   **Target:** 100% Branch Coverage for `src/`.
    *   **Zero-Error Standard:** Software must run with 0 console errors.
*   **Verification Commands:**
    *   `pnpm lint`: Run Biome checks.
    *   `pnpm test:unit`: Run Vitest unit tests.
    *   `pnpm test:e2e`: Run Playwright E2E tests.
    *   `pnpm typecheck`: Run TypeScript type checking.

---

## 10. UI/UX AESTHETIC SINGULARITY (2026 STANDARD)
*   **VISUAL LANGUAGE:**
    *   **Style:** Blend **Liquid Glass** + **Neo-Brutalist** + **Material You 3.0**.
    *   **Motion:** **MANDATORY** fluid animations (`transition: all 0.2s`).
*   **PERFORMANCE UX:**
    *   **INP Optimization:** Interaction to Next Paint < 200ms.
    *   **Optimistic UI:** UI updates instantly; server syncs in background.
*   **INTERACTION DESIGN:**
    *   **Hyper-Personalization:** Adapt layouts based on user behavior.
    *   **Micro-interactions:** Every click/hover must have feedback.
*   **HYPER-CONFIGURABILITY:**
    *   **Mandate:** Every feature/color must be user-configurable via Settings.

---

## 11. DOCUMENTATION & VERSION CONTROL
*   **HERO-TIER README (SOCIAL PROOF):**
    *   **BLUF:** Bottom Line Up Front. Value prop first.
    *   **Live Sync:** Update README **IN THE SAME TURN** as code changes.
    *   **Visuals:** High-Res Badges (Shields.io), ASCII Architecture Trees.
    *   **AI Replication Block:** Include `<details>` with stack info for other agents.
    *   **Social Proof:** Explicitly ask users to **"Star ⭐ this Repo"**.
*   **ADVANCED GIT OPERATIONS:**
    *   **Context Archaeology:** Use `git log`/`git blame`.
    *   **Conventional Commits:** Strict format (`feat:`, `fix:`, `docs:`).
    *   **Semantic Versioning:** Enforce `Major.Minor.Patch`.

---

## 12. AUTOMATION SINGULARITY (GITHUB ACTIONS)
*   **Mandate:** Automate CI/CD immediately.
*   **Workflows:**
    1.  **Integrity:** Lint + Test on Push.
    2.  **Security:** Audit dependencies + SBOM.
    3.  **Release:** Semantic Versioning + Artifact Upload.
    4.  **Deps:** Auto-merge non-breaking updates.

---

## 13. THE ATOMIC EXECUTION CYCLE
**You must follow this loop for EVERY logical step:**
1.  **Audit:** Scan state (`ls -R`) & History (`git log`).
2.  **Research:** Query Best Practices & Trends.
3.  **Plan:** Architect via `clear-thought-two`.
4.  **Act:** Fix Code + Polish + Add Settings + Write Tests (in `tests/`).
5.  **Automate:** Create/Update CI/CD YAMLs.
6.  **Docs:** Update `README.md` (Replication Ready).
7.  **Verify:** Run Tests & Linters.
8.  **REITERATE:** If *any* error/warning exists, fix it immediately.
    **DO NOT STOP** until the build is perfectly clean.
9.  **Commit:** `git commit` immediately (Only when clean).
</details>


## Getting Started

To get TabFlow up and running for development or to install it in your browser, follow these instructions.

### Prerequisites

Ensure you have the following installed:

*   **Node.js:** v18.x or higher (LTS recommended)
*   **pnpm:** v8.x or higher (preferred package manager)
    *   Install pnpm: `npm install -g pnpm`

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension.git
    cd TabFlow-Digital-Journey-Mapper-Browser-Extension
    

2.  **Install dependencies:**
    bash
    pnpm install
    

### Running Locally (Development)

To run the extension in development mode with hot-reloading:

1.  **Start the development server:**
    bash
    pnpm dev
    

2.  **Load the extension in your browser:**
    *   **Chrome/Brave/Edge:**
        1.  Go to `chrome://extensions`.
        2.  Enable "Developer mode" (top right).
        3.  Click "Load unpacked" and select the `dist` directory that `pnpm dev` generates.
    *   **Firefox:**
        1.  Go to `about:debugging#/runtime/this-firefox`.
        2.  Click "Load Temporary Add-on..." and select any file inside the `dist` directory.

### Building for Production

To create a production-ready build for submission to extension stores or for local installation:

1.  **Build the project:**
    bash
    pnpm build
    
    The production-ready extension will be generated in the `dist` directory.

2.  **Load the built extension:** Follow the steps above for "Load unpacked" / "Load Temporary Add-on", pointing to the newly generated `dist` directory.


## Development Setup

### Scripts

This project utilizes `pnpm` scripts for common development tasks:

| Script              | Description                                        |
| :------------------ | :------------------------------------------------- |
| `pnpm dev`          | Starts the development server for hot-reloading.     |
| `pnpm build`        | Builds the extension for production.                 |
| `pnpm lint`         | Lints all `src` files using Biome.                   |
| `pnpm lint:fix`     | Lints and automatically fixes issues using Biome.    |
| `pnpm typecheck`    | Runs TypeScript type checking.                       |
| `pnpm test:unit`    | Runs Vitest unit tests.                              |
| `pnpm test:e2e`     | Runs Playwright end-to-end tests.                    |
| `pnpm test`         | Runs all unit and E2E tests.                         |
| `pnpm preview`      | Serves the production build locally for testing.     |

### Principles

This project strictly adheres to established software development principles to ensure high quality, maintainability, and scalability:

*   **SOLID Principles:** Embracing Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.
*   **DRY (Don't Repeat Yourself):** Eliminating redundant code through abstraction and reusable components.
*   **YAGNI (You Aren't Gonna Need It):** Focusing on current requirements and avoiding premature optimization or over-engineering.
*   **Feature-Sliced Design (FSD):** Structuring the application logically by feature domain, enhancing modularity and isolation for browser extension complexity.


## Contributing

We welcome contributions to TabFlow! Please refer to our [CONTRIBUTING.md](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/.github/CONTRIBUTING.md) for detailed guidelines on how to get started, report bugs, suggest features, and submit pull requests.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License. See the [LICENSE](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/LICENSE) file for more details.

## Security

Your security is our top priority. Please review our [SECURITY.md](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/.github/SECURITY.md) to understand our security practices and how to report vulnerabilities.

## Acknowledgements

Special thanks to the open-source community for providing the tools and libraries that made this project possible, including Node.js, pnpm, WXT, Vite, Vue, Biome, Vitest, and Playwright.