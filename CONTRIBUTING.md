# Contributing to StockSim

This document explains how our team works together and contributes to StockSim.

Contributions can include user stories, tasks, research, app maps, wireframes, prototypes, documentation, code, and tests. Check existing GitHub issues and coordinate with the team before starting work.

## Team Roles

For Sprint 0:

- **Scrum Master:** Abhishek Subedi (`Zho29`)
- **Product Owner:** Hanzalah Siraj (`hanza-siraj`)

These roles rotate each sprint. All members, including the Scrum Master and Product Owner, also do design and development work.

## Communication and Meetings

We use the course Discord team channel for project communication. Important decisions and progress updates should be shared there so teammates and course staff can follow our work.

Our meetings are:

- **Tuesday:** 6:00–7:00 p.m.
- **Thursday:** 9:00–10:00 p.m.

All times are in **America/New_York**.

We follow the course [Team Norms guidance](https://github.com/nyu-software-engineering/scrum-framework/blob/main/team-norms.md). Members are responsible for their contributions, and work must be reviewed by a teammate before merging.

## Tools

- **Code editor:** Visual Studio Code
- **Code linter:** ESLint
- **Version control:** Git and GitHub

The application technology stack and ESLint configuration will be added once they are decided.

## Issues and Task Board

We use GitHub Issues and the StockSim Project to organize work.

- Label user stories as `user story`.
- Label implementation tasks as `task`.
- Label research and environment setup work as `spike`.
- Add the appropriate sprint label, such as `Sprint 0`.
- Assign tasks and spikes to a team member.
- Link each task to its related user story in the issue description.

Tasks should be small enough for one person to complete between standup meetings.

Keep the task board updated using these statuses:

**Todo → In progress → Awaiting Review → Done**

Each sprint has its own backlog and task board. Leave them unchanged after the sprint ends.

Our work estimation method is not yet finalized. We will revisit Planning Poker cards.

## Git Workflow

Everyone works in the same shared repository.

1. Make changes on a temporary or allocated branch.
2. Commit and push changes to that branch.
3. Open a pull request to the team's `master` branch.
4. Have a teammate review the changes.
5. Address any feedback.
6. Merge approved changes into `master` after applicable checks pass.

Use your own GitHub account and descriptive commit messages. Do not push unreviewed changes directly to `master`.

## Local Setup

Install Git and Visual Studio Code, then clone the shared repository:

```bash
git clone https://github.com/agile-students-fall2026/StockSim.git
cd StockSim
```

Open the folder in Visual Studio Code. Make sure your Git author name matches your GitHub username, as required by the course.

Additional dependency and environment setup instructions will be added after the team chooses the technology stack.

Do not commit passwords, API keys, or other sensitive information. Follow the repository's `.gitignore`.

## Building and Testing

Everyone must provide appropriate tests for the code they write and ensure that the code passes all necessary checks before merging it into `master`.

Build, run, and test commands will be added when the application reaches the development stage.


