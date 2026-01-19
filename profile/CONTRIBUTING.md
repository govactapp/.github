# Contributing to Ice Guard

Thank you for your interest in contributing to **Ice Guard**.

Ice Guard is a public-interest, fully open-source project focused on **situational awareness and documentation**, not advocacy or enforcement. Contributions are welcome, but they must align with the project’s goals of **safety, neutrality, transparency, and durability**.

This document outlines how to contribute effectively and responsibly.

---

## Guiding Principles for Contributors

Before contributing, please understand the principles that guide this project:

- **Safety over speed** — features that introduce harm risk will not be merged
- **Neutral infrastructure** — the platform documents; it does not editorialize
- **Transparency by default** — logic should be clear and auditable
- **Resilience matters** — changes should support redeployability and longevity
- **Good faith collaboration** — this is not a battleground

If a proposed change conflicts with these principles, it is unlikely to be accepted.

---

## Ways to Contribute

Contributions are welcome in many forms, including:

- Bug fixes
- Performance improvements
- Accessibility and UX improvements
- Geospatial querying and visualization
- Abuse prevention and moderation tooling
- Documentation and clarity improvements
- Test coverage
- Deployment and reproducibility tooling

If you are unsure whether an idea fits, **open a discussion or issue first**.

---

## Getting Started

### 1. Fork the Repository
Create your own fork of the Ice Guard repository on GitHub.

### 2. Clone Your Fork
```sh
git clone https://github.com/<your-username>/ice-guard.git
cd ice-guard
```

### 3. Follow Setup Instructions
Refer to `README.md` and `DEPLOYMENT.md` (if present) for local setup instructions.

If documentation is unclear or missing, improving it is a valid contribution.

---

## Development Workflow

### Branching
- Create a feature branch from `main`
- Use descriptive branch names:
  - `fix/map-rendering`
  - `feat/location-bounding`
  - `docs/privacy-clarifications`

### Commits
- Write clear, descriptive commit messages
- Prefer small, focused commits over large, mixed changes

---

## Pull Requests

### Before Opening a PR
Please ensure that:
- The change aligns with Ice Guard’s guiding principles
- Code is formatted and linted according to project standards
- Tests are updated or added where appropriate
- Documentation is updated if behavior changes

### PR Expectations
- Describe **what** the change does and **why**
- Explain any security, privacy, or safety implications
- Reference related issues or discussions if applicable

Large or controversial changes should be discussed **before** implementation.

---

## What Will Not Be Accepted

To keep the project focused and safe, the following types of contributions will not be accepted:

- Features that enable real-time tracking or coordination
- Content that encourages confrontation, evasion, or harassment
- Changes that expose precise residential locations
- Political messaging, slogans, or editorial language
- Attempts to bypass moderation or safety constraints
- “Rewrite everything” PRs without prior discussion

This is not a judgment of intent — it is a boundary for the project.

---

## Security Issues

**Do not** report security vulnerabilities via public issues or pull requests.

If you discover a security issue:
- Follow the guidance in `SECURITY.md`
- Provide sufficient detail for reproduction
- Allow time for responsible disclosure

---

## Moderation & Policy Changes

Changes that affect:
- content rules
- moderation logic
- data handling
- privacy guarantees
- location processing

**require discussion first**.

These areas are core to the project’s trust model and must be handled carefully.

---

## Code of Conduct

All contributors are expected to follow the project’s `CODE_OF_CONDUCT.md`.

Harassment, threats, doxxing, or bad-faith engagement — even when framed as “passion” — will not be tolerated.

---

## Licensing

By contributing to Ice Guard, you agree that your contributions will be licensed under the project’s **AGPL-3.0** license.

This ensures that Ice Guard remains open, auditable, and redeployable.

---

## Final Note

Ice Guard is intended to outlast any single deployment, maintainer, or moment.

Contributions that strengthen clarity, safety, and resilience are valued more than contributions that chase novelty or speed.

If you’re here to build something careful, durable, and useful — welcome.
