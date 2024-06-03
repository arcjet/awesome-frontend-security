# Awesome Frontend Security [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) <!-- omit from toc -->

A curated list of resources for learning about application security and securing your frontend applications.

## Contents <!-- omit from toc -->

- [Guides](#guides)
- [Cheat Sheets](#cheat-sheets)
- [Libraries](#libraries)
- [Tools](#tools)
  - [Code scanning](#code-scanning)
  - [Supply Chain Security](#supply-chain-security)
  - [Testing](#testing)
- [Courses](#courses)

## Guides

- [How to Think About Security in Next.js](https://nextjs.org/blog/security-nextjs-server-components-actions)
- [Secret scanning and Next.js builds](https://blog.arcjet.com/secret-scanning-and-next-js-builds/)

## Cheat Sheets

- [Authentication Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
- [CSP Cheat Sheet](https://scotthelme.co.uk/csp-cheat-sheet/)
- [XSS Filter Evasion Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html)

## Libraries

- [Helmet](https://github.com/helmetjs/helmet) - Middleware to set HTTP security headers for Express applications.
- [next-safe](https://github.com/trezy/next-safe) - A simple way to configure CSP headers in Next.js applications.
- [server-only](https://www.npmjs.com/package/server-only) - Ensure your code is only run on the server.
- [Valibot](https://valibot.dev/) - A library for validating data.
- [Zod](https://zod.dev/) - TypeScript-first validation library.

## Tools

### Code scanning

- [Gitleaks](https://github.com/gitleaks/gitleaks) - Scans git repositories for secrets.
- [Semgrep](https://semgrep.dev/) - Static analysis tool for finding bugs and enforcing code standards.
- [Trufflehog](https://github.com/trufflesecurity/trufflehog) - Searches for secrets and other sensitive information.

### Supply Chain Security

- [Dependabot](https://docs.github.com/en/code-security/dependabot) - Automated dependency updates as PRs.
- [npm-audit](https://docs.npmjs.com/cli/v10/commands/npm-audit) - Built into npm, run `npm audit` to check for vulnerabilities in your dependencies.
- [Socket](https://socket.dev/) - Dependency analysis and reporting for security and licensing issues.

### Testing

- [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Check your CSP headers for common issues.
- [shcheck](https://github.com/santoru/shcheck) - A CLI for checking website security headers.

## Courses

- [Stanford CS 253 Web Security](https://web.stanford.edu/class/cs253/) - Comprehensive overview of web security (Fall 2021).
