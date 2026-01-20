![govactapp-banner](../images/govactapp-banner-dark.png#gh-dark-mode-only)
![govactapp-banner](../images/govactapp-banner-light.png#gh-light-mode-only)

Back to [README.md > Get Involved](../README.md#get-involved)

# Contributing to GovAct

Thank you for your interest in contributing to **GovAct**.

GovAct is a public-interest, fully open-source project focused on **situational awareness and durable documentation**. It is not advocacy, not enforcement, and not a real-time coordination or alerting system.

Contributions are welcome, but they must align with the project’s goals of **safety, neutrality, transparency, and long-term resilience**.

---

## Guiding Principles for Contributors

GovAct is built around the following principles:

- **Safety over speed** — features that introduce harm risk will not be merged
- **Neutral infrastructure** — the platform documents; it does not editorialize
- **Transparency by default** — logic should be clear and auditable
- **Resilience matters** — changes should support redeployability and longevity
- **Good-faith collaboration** — this is not a battleground

If a proposed change conflicts with these principles, it is unlikely to be accepted.

---

## Is This the Right Project for Your Idea?

GovAct is not a general civic forum or political platform.

If your goal is to:
- promote a political position or messaging
- mobilize action or coordination
- identify, track, or target individuals
- enable confrontation or evasion
- introduce real-time alerts or warnings

this project is likely **not** the right venue.

If your goal is to:
- improve safety, privacy, or harm reduction
- strengthen documentation quality and clarity
- improve resiliency, auditability, or deployability
- enhance geospatial accuracy *without increasing risk*
- reduce abuse or improve moderation tooling

you are likely in the right place.

---

## Ways to Contribute

Contributions are welcome in many forms, including:

- Bug fixes and reliability improvements
- Performance improvements
- Accessibility and UX improvements
- Geospatial querying and visualization
- Abuse prevention and moderation tooling
- Documentation and clarity improvements
- Test coverage and CI improvements
- Deployment and reproducibility tooling

If you are unsure whether an idea fits, **open an issue or discussion first**.

---

## Getting Started

### 1) Fork the Repository

Create your own fork of the GovAct repository on GitHub.

### 2) Clone Your Fork

```sh
git clone https://github.com/<your-username>/govact.git
cd govact
```

### 3) Follow Setup Instructions

Refer to `README.md` and any deployment documentation (if present) for local setup instructions.

If documentation is unclear or missing, improving it is a valid and welcome contribution.

---

## Development Workflow

### Branching

- Create a feature branch from `main`
- Use descriptive branch names, such as:
  - `fix/map-rendering`
  - `feat/location-bounding`
  - `docs/privacy-clarifications`

### Commits

- Write clear, descriptive commit messages
- Prefer small, focused commits over large or mixed changes

---

## Pull Requests

### Before Opening a PR

Please ensure that:

- The change aligns with GovAct’s guiding principles
- Code is formatted and linted according to project standards
- Tests are updated or added where appropriate
- Documentation is updated if behavior changes
- Safety, privacy, and abuse implications are explicitly considered

### PR Expectations

In your pull request description, include:

- **What** the change does
- **Why** it is needed
- Any privacy, safety, or security implications
- Links to related issues or discussions

Large or controversial changes should be discussed **before** implementation.

---

## What Will Not Be Accepted

To keep the project safe and focused, the following contributions will not be accepted:

- Features that enable real-time tracking or coordination
- Changes that expose precise residential locations
- Content that encourages confrontation, evasion, or harassment
- Political messaging, slogans, or editorial language
- Attempts to bypass moderation or safety constraints
- Large refactors without prior discussion

This is not a judgment of intent — it is a boundary for the project.

---

## Policy-Sensitive Changes (Discuss First)

Changes affecting any of the following require discussion first:

- Content rules or enforcement logic
- Moderation workflows
- Location processing or accuracy bounding
- Media handling and metadata stripping
- Privacy guarantees
- Authentication or authorization boundaries

These areas define the platform’s trust model.

---

## Security Issues

**Do not** report security vulnerabilities via public issues or pull requests.

If you discover a security issue, follow the instructions in `SECURITY.md`.

---

## Code of Conduct

All contributors must follow `CODE_OF_CONDUCT.md`.

Harassment, threats, doxxing, or bad-faith engagement will not be tolerated.

---

## Licensing

By contributing to GovAct, you agree that your contributions will be licensed under the project’s **AGPL-3.0** license.

---

## Final Note

GovAct is intended to outlast any single deployment, maintainer, or moment.

Contributions that strengthen clarity, safety, and resilience are valued more than contributions that prioritize speed or novelty.

If you’re here to build something careful, durable, and useful — welcome.