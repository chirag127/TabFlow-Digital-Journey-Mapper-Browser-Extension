# TabFlow-Digital-Journey-Mapper-Browser-Extension

![TabFlow Logo](https://raw.githubusercontent.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/main/.github/assets/tabflow-banner.png)

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/ci.yml?branch=main&style=flat-square&label=Build)](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/main?style=flat-square&label=Coverage)](https://codecov.io/gh/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension)
[![Tech Stack](https://img.shields.io/badge/Stack-JS%20%7C%20WXT%20%7C%20Vite-blueviolet?style=flat-square)](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension#ai-agent-directives)
[![Lint & Format](https://img.shields.io/badge/Lint%2FFmt-Biome-33CC99?style=flat-square)](https://biomejs.dev/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension?style=flat-square&colorA=1F2228&colorB=2A2E33)](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/stargazers)

**Star ⭐ this Repo!** Your support helps us grow and deliver more powerful tools.

## Bottom Line Up Front (BLUF)

TabFlow is an advanced browser extension meticulously tracking and visualizing digital journeys, transforming browsing history into interactive, graph-based maps. It reveals click paths and referral chains, providing unparalleled insights into navigation patterns, understanding habits, and optimizing online exploration with a strong focus on privacy.

## 📖 Table of Contents

-   [Bottom Line Up Front (BLUF)](#bottom-line-up-front-bluf)
-   [📖 Table of Contents](#-table-of-contents)
-   [🤖 AI Agent Directives](#-ai-agent-directives)
-   [✨ Key Features](#-key-features)
-   [🚀 Getting Started](#-getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
    -   [Loading the Extension](#loading-the-extension)
-   [🛠️ Development Scripts](#%EF%B8%8F-development-scripts)
-   [💡 Core Architectural Principles](#-core-architectural-principles)
-   [🗺️ Architecture Overview](#%EF%B8%8F-architecture-overview)
-   [🤝 Contributing](#-contributing)
-   [📜 License](#-license)
-   [📞 Support & Contact](#-support--contact)

## 🤖 AI Agent Directives

<details>
<summary>For Future AI Agents: Core System Directives (TabFlow)</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This project is a **JavaScript Browser Extension**.
*   **Stack:** **WXT 0.16.x** (Web Extension Framework), **Vite 7** (Rolldown for build), **JavaScript ES2023** (Standard), **TailwindCSS v4** (Styling).
*   **State:** **Signals** (Standardized via custom store or dedicated library).
*   **Lint/Test:** **Biome** (Speed, Lint, Format) + **Vitest** (Unit) + **Playwright** (E2E).

---

## 4. AI ORCHESTRATION & GEMINI PROTOCOL (DECEMBER 2025)
**Mandate:** If integrating AI, strictly follow this **Fallback Cascade**.
*   **Tier 1 (Intelligence):** `gemini-3-pro` (Stable Dec 2025) - Multimodal Reasoning.
*   **Tier 2 (Reasoning):** `gemini-2.5-pro` (Legacy Stable) - Deep analysis/STEM.
*   **Tier 3 (Balanced):** `gemini-2.5-flash` - High Volume/Low Latency.
*   **Tier 4 (Speed):** `gemini-2.5-flash-lite` - Cost-efficiency.
*   **Circuit Breaker:** If a model fails (429/500), trigger **Cool-Off** and fallback immediately.

---

## 5. RECURSIVE PERFECTION LOOP (THE "ZERO-ERROR" MANDATE)
**The Loop:**
1.  **Analyze:** Scan the codebase.
2.  **Fix:** Apply architectural patterns and fixes.
3.  **Lint/Format:** Run the stack's strictest linter (Biome/Ruff).
4.  **Test:** Run the test suite.
5.  **DECISION GATE:**
    *   **IF** Errors/Warnings exist -> **GO TO STEP 2** (Self-Correct).
    *   **IF** Clean -> **COMMIT** and Present.
**Constraint:** **DO NOT STOP** until the build is perfectly clean.

---

## 6. CORE ARCHITECTURAL PRINCIPLES
*   **SOLID MANDATE:** SRP, OCP, LSP, ISP, DIP.
*   **ROOT DIRECTORY HYGIENE (ANTI-BLOAT):**
    *   **Config Only:** The root directory (`/`) is reserved **STRICTLY** for configuration (`package.json`, `README.md`, `.gitignore`).
    *   **No Root Scripts:** Do not create a `scripts/` folder in the root.
    *   **Containment:** All source code goes to `extension/`. All verification code goes to `tests/`.
*   **MODULARITY:** Feature-First Structure (`extension/features/graph-viewer`), not type.
*   **CQS:** Methods must be **Commands** or **Queries**, never both.
*   **12-Factor App:** Config in environment; backing services attached.

---

## 7. CODE HYGIENE & STANDARDS (READABILITY FIRST)
*   **SEMANTIC NAMING PROTOCOL:**
    *   **Descriptive Verbs:** `trackNavigationEvent` (Good) vs `nav` (Bad).
    *   **Casing:** `camelCase` (JS).
*   **CLEAN CODE RULES:**
    *   **Verticality:** Optimize for reading down.
    *   **No Nesting:** Use **Guard Clauses** (`return early`).
    *   **DRY & KISS:** Automate repetitive tasks. Keep logic simple.
    *   **Zero Comments:** Code must be **Self-Documenting**. Use comments *only* for "Why".

---

## 8. RELIABILITY, SECURITY & SUSTAINABILITY
*   **DEVSECOPS PROTOCOL:**
    *   **Zero Trust:** Sanitize **ALL** inputs (OWASP Top 10 2025), especially from browser events.
    *   **Supply Chain:** Generate **SBOMs** for all builds.
    *   **Fail Fast:** Throw errors immediately on invalid state.
    *   **Encryption:** Secure sensitive user browsing data locally (IndexedDB) and in transit.
*   **EXCEPTION HANDLING:**
    *   **Resilience:** App must **NEVER** crash. Wrap critical I/O in `try-catch-finally`.
    *   **Recovery:** Implement retry logic with exponential backoff for API calls (if any).
*   **GREEN SOFTWARE:**
    *   **Rule of Least Power:** Choose the lightest tool for the job.
    *   **Efficiency:** Optimize graph algorithms and data processing for minimal CPU/memory.
    *   **Lazy Loading:** Load heavy visualization libraries only when the graph view is active.

---

## 9. COMPREHENSIVE TESTING & VERIFICATION STRATEGY
*   **FOLDER SEPARATION PROTOCOL (STRICT):**
    *   **Production Purity:** The `extension/` folder is a **Production-Only Zone**. It must contain **ZERO** test files and **ZERO** test scripts.
    *   **Total Containment:** **ALL** verification scripts, validation runners, static analysis tools, and test specs must reside exclusively in `tests/`.
    *   **Structure:**
        *   `tests/unit/`: Vitest unit tests for individual functions and modules.
        *   `tests/e2e/`: Playwright end-to-end tests simulating browser interaction and extension functionality.
        *   `tests/scripts/`: Verification/Validation scripts (e.g., `verify-manifest.js`, `audit-permissions.js`).
*   **TESTING PYRAMID (F.I.R.S.T.):**
    *   **Fast:** Tests run in milliseconds.
    *   **Isolated:** No external dependencies (mock browser APIs).
    *   **Repeatable:** Deterministic results.
*   **COVERAGE MANDATE:**
    *   **1:1 Mapping:** Every source file in `extension/` **MUST** have a corresponding test file.
    *   **Target:** 100% Branch Coverage.
    *   **Zero-Error Standard:** Software must run with 0 console errors.

---

## 10. UI/UX AESTHETIC SINGULARITY (2026 STANDARD)
*   **VISUAL LANGUAGE:**
    *   **Style:** Blend **Liquid Glass** + **Neo-Brutalist** + **Material You 3.0** for extension popup and options pages.
    *   **Motion:** **MANDATORY** fluid animations (`transition: all 0.2s`) for graph interactions and UI transitions.
*   **PERFORMANCE UX:**
    *   **INP Optimization:** Interaction to Next Paint < 200ms for all user interactions within the extension.
    *   **Optimistic UI:** UI updates instantly; background scripts sync data asynchronously.
*   **INTERACTION DESIGN:**
    *   **Hyper-Personalization:** Adapt graph layouts and visualization preferences based on user interaction history.
    *   **Micro-interactions:** Every click/hover on graph nodes/edges must have visual feedback.
*   **HYPER-CONFIGURABILITY:**
    *   **Mandate:** Every visualization parameter (color, node size, edge thickness, layout algorithm) must be user-configurable via Settings.

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
    3.  **Release:** Semantic Versioning + Artifact Upload (e.g., to Chrome Web Store/Firefox Add-ons).
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

## ✨ Key Features

*   **Interactive Digital Journey Maps:** Visualize browsing history as dynamic, explorable graph structures.
*   **Click Path & Referral Chain Analysis:** Understand exactly how you navigate the web and discover source origins.
*   **Privacy-Focused Tracking:** All data is processed and stored locally within your browser, ensuring no external servers receive your personal browsing information.
*   **Advanced Data Visualization:** Utilizes modern web technologies to render complex graph layouts with high performance.
*   **Search & Filter Capabilities:** Easily find specific pages, domains, or paths within your journey maps.
*   **Time-Based Segmentation:** Analyze browsing patterns over custom time ranges.
*   **Export & Archive:** Save your journey maps for later analysis or sharing (locally).

## 🚀 Getting Started

Follow these steps to get TabFlow up and running in your browser for development or immediate use.

### Prerequisites

Ensure you have the following installed:

*   [Node.js](https://nodejs.org/en/) (LTS version recommended)
*   [npm](https://www.npmjs.com/) (usually comes with Node.js)
*   A modern web browser (e.g., Chrome, Firefox, Edge)

### Installation

1.  **Clone the Repository:**

    bash
    git clone https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension.git
    cd TabFlow-Digital-Journey-Mapper-Browser-Extension
    

2.  **Install Dependencies:**

    bash
    npm install
    

3.  **Build the Extension:**

    bash
    npm run build
    
    This will create a `dist/` directory containing the production-ready extension files.

### Loading the Extension

#### Chrome/Edge

1.  Open your browser and navigate to `chrome://extensions` (or `edge://extensions`).
2.  Enable "Developer mode" (usually a toggle in the top right).
3.  Click "Load unpacked" and select the `dist` directory from your cloned repository.

#### Firefox

1.  Open Firefox and navigate to `about:debugging#/runtime/this-firefox`.
2.  Click "Load Temporary Add-on...".
3.  Navigate to the `dist` directory and select any file inside (e.g., `manifest.json`).

## 🛠️ Development Scripts

Here are the essential scripts for development:

| Script          | Description                                         |
| :-------------- | :-------------------------------------------------- |
| `npm run dev`   | Starts the development server with hot-reloading.   |
| `npm run build` | Builds the extension for production.                |
| `npm run lint`  | Lints all `extension/` files using Biome.           |
| `npm run format`| Formats all `extension/` files using Biome.         |
| `npm run test`  | Runs all unit tests with Vitest.                    |
| `npm run test:e2e`| Runs end-to-end tests with Playwright.              |

## 💡 Core Architectural Principles

This project adheres strictly to modern software engineering principles to ensure maintainability, scalability, and robustness:

*   **S.O.L.I.D Principles:** Ensuring single responsibility, open/closed, Liskov substitution, interface segregation, and dependency inversion.
*   **D.R.Y. (Don't Repeat Yourself):** Promoting reusable code and discouraging redundancy.
*   **K.I.S.S. (Keep It Simple, Stupid):** Prioritizing simplicity and clarity in design and implementation.
*   **Y.A.G.N.I. (You Ain't Gonna Need It):** Avoiding premature optimization and unnecessary features.
*   **Feature-Sliced Design (FSD):** Organizing the codebase into layers and slices based on features for better modularity and understanding.

## 🗺️ Architecture Overview

TabFlow's architecture is designed for modularity, performance, and clear separation of concerns, following the Feature-Sliced Design (FSD) approach within the browser extension context.

mermaid
graph TD
    A[Browser] --> B(Extension Popup)
    B --> C{Background Script}
    C --> D[Content Script]
    C --> E[Data Store]
    E --> F[Graph Visualization Engine]
    F --> B
    
    subgraph Extension Core
        C -- Events --> D
        C -- Data Sync --> E
    end

    subgraph Data Processing
        E[Data Store] -- Persist --> G(IndexedDB)
        E -- Retrieve --> F
    end

    subgraph UI Layers
        B -- User Input --> C
        F -- Render Graph --> B
    end
    
    G -- Local Data Storage --> H[Browser Environment]
    D -- DOM Interaction --> I[Web Page]



tree -L 2
. 
├── .github/
│   ├── workflows/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
├── extension/
│   ├── assets/
│   ├── components/
│   ├── features/
│   ├── pages/
│   └── scripts/
├── public/
├── tests/
│   ├── e2e/
│   └── unit/
├── .gitignore
├── AGENTS.md
├── badges.yml
├── biome.json
├── CONTRIBUTING.md
├── LICENSE
├── package.json
├── PROPOSED_README.md
├── README.md
├── SECURITY.md
└── vite.config.js


## 🤝 Contributing

We welcome contributions from the community! Whether it's reporting a bug, suggesting a feature, or submitting a pull request, your help is invaluable. Please refer to our [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## 📜 License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](LICENSE) License.

## 📞 Support & Contact

For questions, issues, or feedback, please open an issue on the [GitHub Issue Tracker](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/issues).