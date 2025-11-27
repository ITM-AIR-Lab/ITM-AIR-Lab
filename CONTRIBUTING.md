# Contributing to ITM AIR Lab

Thank you for your interest in contributing! This document describes how to propose work, submit contributions, and join the lab.

Getting started
1. Read the main README to understand lab goals and structure.
2. Join the lab communication channels (Slack/Discord / email) — list maintained on the website.
3. Pick an area: Research, Data, or Development.

Project proposals
- Open an issue describing the proposed project, expected deliverables, timeline, and department.
- Use the template: Goal, Motivation, Approach, Resources needed, Timeline, Potential mentors.

Code & experiments
- Create feature branches named like: dept/short-description (e.g., research/llm-ft-textbook).
- Write clear commit messages and keep PRs small and focused.
- Include reproducible steps, random seeds, environment specs, and hardware used.
- Provide model cards and dataset licenses for all releases.

PR review & merging
- At least one department lead or assigned reviewer must approve.
- CI must pass (unit tests, linting, basic training smoke tests).
- Squash or rebase as needed; maintain a clear history.

Data
- Include provenance, licenses, and annotation guidelines.
- Follow privacy and ethics rules — do not include PII or restricted content.

Code style & dependencies
- Use Python 3.10+ (or lab-specified environment).
- Provide environment.yml or requirements.txt for experiments.
- Run flake8/black for Python; add formatters for other languages.

Community guidelines
- Be respectful and collaborative.
- File issues for bugs, feature requests, or process suggestions.

If you want help onboarding, request a mentor in the #onboarding channel.
