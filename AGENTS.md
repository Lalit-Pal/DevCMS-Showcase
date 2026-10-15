# DevCMS Showcase — Agent Instructions

## Purpose

Maintain the public documentation repository for DevCMS, a deployed personal portfolio website and content management system.

The application source code is maintained separately in the private `dev-cms` repository. This repository is for project presentation and documentation only.

## Repository Rules

- Keep all showcase work inside this repository.
- Never copy application source code, backend implementation files, environment files, credentials, API keys, tokens, database connection strings, private user data, or other secrets into this repository.
- Never change the visibility of either GitHub repository.
- Never modify application deployment configuration or production data while working on the showcase.
- Never push, pull, or commit changes in the parent `dev-cms` repository as part of showcase work.
- Never publish changes to GitHub without explicit user approval.

## Documentation Accuracy

- Inspect the actual application before documenting its features, technologies, architecture, and deployment.
- Describe only implemented and verified functionality as complete.
- Clearly distinguish implemented features from planned improvements.
- Do not invent performance metrics, user counts, test results, security guarantees, or business outcomes.
- Explain important engineering decisions and trade-offs when supported by evidence.
- Keep the README concise, professional, and useful to recruiters and engineering interviewers.

## Screenshots and Assets

- Store approved project screenshots in `screenshots/`.
- Use genuine screenshots of the running application or approved design assets.
- Never include passwords, access tokens, private account information, confidential customer data, or sensitive admin information.
- Do not fabricate screenshots or claim that planned features are implemented.
- Flag missing or outdated screenshots for the user to review.

## Keeping Documentation Current

When the user requests a showcase update after an application change:

1. Inspect the relevant application changes.
2. Identify which documentation or screenshots need updating.
3. Update only the relevant showcase files.
4. Check links, file references, technical claims, and consistency.
5. Summarize the changes and identify anything requiring user verification.
6. Wait for explicit approval before committing or pushing.

Do not modify application source files unless separately requested.

## Initial Deliverables

Prepare:

- `README.md` — project overview, public portfolio link, product modules, technology stack, screenshots, architecture overview, and future improvements.
- `docs/architecture.md` — system architecture and request/data flow.
- `docs/engineering-decisions.md` — engineering decisions, rationale, and trade-offs.

Do not create unnecessary documentation or claim details that cannot be verified.