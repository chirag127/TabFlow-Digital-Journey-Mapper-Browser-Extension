# Security Policy

## Supported Versions

We are committed to providing a secure product. The following versions are actively supported with security patches:

| Version        | Supported          |
| -------------- | ------------------ |
| `main` (latest)| :white_check_mark: |
| `1.x.x`        | :white_check_mark: |

Older versions are not actively maintained and may contain known vulnerabilities.

## Reporting a Vulnerability

We take all security vulnerabilities seriously. If you discover a security issue, please report it to us following these steps:

1.  **DO NOT** open a public issue.
2.  **DO NOT** disclose the vulnerability publicly until it has been fixed and a patch is released.
3.  Send a detailed email to our dedicated security team at: `security@tabflow.dev`.

Your email should include:

*   A clear and concise description of the vulnerability.
*   Steps to reproduce the vulnerability.
*   Information about the affected version(s) and environment.
*   Any proof-of-concept (PoC) code or evidence.
*   Your contact information for follow-up.

We will acknowledge receipt of your report within **48 hours** and will make a best effort to address it promptly. We will also inform you once the vulnerability has been fixed and will give credit for responsible disclosure.

## Security Best Practices

We encourage users and developers to follow these best practices to ensure the security of their usage of TabFlow:

*   **Privacy First:** TabFlow is designed with privacy at its core. Browsing history is processed locally within the browser extension and is not transmitted to any external servers. However, always be mindful of what data you are choosing to analyze.
*   **Stay Updated:** Regularly update TabFlow to the latest version to ensure you have the most recent security patches and features.
*   **Browser Security:** Maintain good browser security hygiene. Ensure your browser is up-to-date and that you use reputable security extensions.
*   **Code Contributions:** If you are contributing code, please adhere to our contributing guidelines and ensure your contributions do not introduce security risks. All contributions are subject to security review.

## Security Audits and Tools

We utilize automated tools and perform regular audits to identify and mitigate potential security risks:

*   **Dependency Scanning:** We regularly scan our dependencies for known vulnerabilities using tools like `npm audit` and GitHub's Dependabot.
*   **Static Analysis:** Code is analyzed using linters and static analysis tools (e.g., Biome) to catch potential security anti-patterns early.
*   **Dynamic Analysis:** End-to-end tests using Playwright are run to simulate user interactions and identify potential runtime issues.
*   **SBOM Generation:** Software Bill of Materials (SBOMs) are generated for all releases to provide transparency into the components used.

## Responsible Disclosure Policy

We are committed to a responsible disclosure process. Upon receiving a security report, we will:

1.  Investigate the reported vulnerability.
2.  Develop and test a fix.
3.  Release a patched version of the software.
4.  Communicate the fix to our users and acknowledge the reporter.

Thank you for helping keep TabFlow secure.