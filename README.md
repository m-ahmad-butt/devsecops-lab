# DevSecOps Lab Task API

Small Express API for Lab 10. The repository demonstrates secret scanning, static analysis, dependency auditing, container scanning, SBOM creation, Dependabot, and required pull request checks.

Run `npm ci` and `npm start`, then open `http://localhost:3000/health`.

Set `PAYMENT_API_KEY` in the environment when using the payment provider. No key is stored in this repository.

The four GitHub Actions workflows scan for secrets, unsafe code patterns, vulnerable dependencies, and container issues. The container workflow also uploads a CycloneDX SBOM.
