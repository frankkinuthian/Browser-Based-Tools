# Project Workflow & Kanban Guide

This repository uses a professional Kanban workflow managed via **GitHub Projects** and standardized issue templates.

## Kanban Process

- All work is tracked as **Issues** in the repository.
- Issues are organized in a GitHub Project board with columns such as:
  - To do
  - In progress
  - Review
  - Done
- Move issues across columns as work progresses.
- Link Pull Requests to Issues (e.g., `Closes #12`) to automate board updates.

## Issue Templates

- Use the provided issue templates in `.github/ISSUE_TEMPLATE/` for consistency.
- For new features or enhancements, use the **Feature Request** template: [`added_features.md`](ISSUE_TEMPLATE/added_features.md)
- Fill out the summary, acceptance criteria, and any additional context to ensure clarity.

## How to Use GitHub Projects

1. Go to the **Projects** tab in the repository.
2. Select the active Kanban board.
3. Add new or existing issues to the board.
4. Drag issues between columns as their status changes.
5. Reference issues in Pull Requests to keep everything in sync.

## Automation

- (Optional) GitHub Actions in `.github/workflows/` can be used for CI/CD, labeling, or other automation, but do not define the Kanban board itself.

## Contribution Guidelines

- Always use an issue template when proposing new work.
- Keep issues up to date with status and context.
- Use clear, descriptive commit messages and PR titles.

---

For questions about the workflow, see this README or contact a maintainer.
