<p align="center">
  <a href="https://www.getcanyon.ai/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/getcanyon-ai/canyon/main/.github/assets/canyon-mark-dark.svg">
      <img src="https://raw.githubusercontent.com/getcanyon-ai/canyon/main/.github/assets/canyon-mark-light.svg" width="64" height="64" alt="Canyon">
    </picture>
  </a>
</p>

## Your coding agents ship apps. Canyon reviews every deploy.

Canyon is an open-source review gate and app platform for software built with AI. Your agent deploys, Canyon checks the code against your org's rules, the agent gets findings it can fix, and a person promotes to production. It runs on your laptop or your Kubernetes.

| 1. Your agent deploys | 2. Canyon checks it | 3. A person promotes |
|---|---|---|
| `canyon deploy` from Claude Code, Codex or Cursor. | Open-source scanners, and an AI review when you give it a model, check every version against your org's rules. A blocking finding stops the deploy and tells the agent how to fix it. | Production only takes a version that passed review, and a person decides when it goes live. |

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/getcanyon-ai/.github/main/profile/img/01-blocked-dark.png">
    <img src="https://raw.githubusercontent.com/getcanyon-ai/.github/main/profile/img/01-blocked-light.png" width="49%" alt="Canyon's app page: the version is blocked by one finding, SQL built from the request in server.js, with the fix to make">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/getcanyon-ai/.github/main/profile/img/02-passed-dark.png">
    <img src="https://raw.githubusercontent.com/getcanyon-ai/.github/main/profile/img/02-passed-light.png" width="49%" alt="Canyon's app page: the next version passed review and is ready for production">
  </picture>
</p>

Blocked: the agent built SQL from the request. · Passed: after the agent's one-line fix.

### Where to start

<p>
  <a href="https://www.getcanyon.ai/docs/start/take-the-tour/"><img src="https://img.shields.io/badge/Try%20it%20on%20your%20laptop-5865F2?style=for-the-badge" alt="Try it on your laptop"></a>
  <a href="https://www.getcanyon.ai/docs/self-host/kubernetes/"><img src="https://img.shields.io/badge/Run%20it%20for%20your%20team-5865F2?style=for-the-badge" alt="Run it for your team"></a>
  <a href="https://github.com/getcanyon-ai/canyon/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contribute-5865F2?style=for-the-badge" alt="Contribute"></a>
</p>

- **Try it on your laptop.** Paste one prompt into Claude Code, Codex or Cursor. It starts a demo Canyon and walks you through a blocked deploy, the fix, and production. → https://www.getcanyon.ai/docs/start/take-the-tour/
- **Run it for your team.** Install Canyon on your own Kubernetes, with your team's sign-in. → https://www.getcanyon.ai/docs/self-host/kubernetes/
- **Contribute.** Read CONTRIBUTING, then pick an open issue. → https://github.com/getcanyon-ai/canyon/blob/main/CONTRIBUTING.md

<sub>The core is AGPL-3.0, the CLI and contracts are Apache-2.0, and ee/ is under the Elastic License 2.0. Report security issues privately through the repository's Security tab.</sub>
