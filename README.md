# henockMuhye-PracticeRepo

A personal practice repository used for experimenting with Git workflows, GitHub Actions, and AI-assisted development with [Claude Code](https://claude.ai/code).

## Overview

This repository serves as a sandbox for learning and practicing:

- **Git fundamentals** — branching, committing, and managing files
- **GitHub Actions** — automated workflows triggered by repository events
- **Claude Code integration** — AI-assisted code reviews and issue resolution via `@claude` mentions

## Repository Structure

```
henockMuhye-PracticeRepo/
├── PracticeDirectory/
│   └── PracticeFile.txt    # Sample practice file
├── .github/
│   └── workflows/
│       ├── claude.yml              # Claude Code action (triggered by @claude)
│       └── claude-code-review.yml  # Automated code review workflow
├── LICENSE                 # Apache 2.0 License
└── README.md
```

## Claude Code Integration

This repo is set up with the [Claude Code Action](https://github.com/anthropics/claude-code-action), which allows Claude to assist directly within GitHub issues and pull requests.

**How to use:** Mention `@claude` in any issue comment or PR comment to ask Claude for help — reviewing code, answering questions, or implementing changes.

Example:
```
@claude please review and fix the issue described above.
```

## License

Licensed under the [Apache License 2.0](LICENSE).
