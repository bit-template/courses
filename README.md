# Courses Repository

## Overview

The **Courses Repository** is the central learning hub for the BIT Guidances ecosystem.

It provides structured learning materials, learning paths, practical assignments, and technical resources used across all projects.

Instead of duplicating training content in every repository, this repository maintains a single source of truth for learning resources.

The repository supports:

- Internship Program
- Research Support Program
- Open Source Contributors
- AI Agent Development
- FaaS Platform Development
- Community Infrastructure Projects
- Software Engineering Training

---

# Objectives

This repository aims to:

- Standardize technical training
- Define structured learning paths
- Organize technical resources
- Track available courses
- Provide practical assignments
- Support continuous learning

---

# Repository Structure

```text
courses/
│
├── README.md
├── COURSE_CATALOG.md
├── LEARNING_PATHS.md
├── CONTRIBUTING.md
├── ROADMAP.md
│
├── learning-paths/
│   ├── foundation.md
│   ├── research.md
│   ├── faas.md
│   ├── ai-agents.md
│   ├── devops.md
│   ├── cybersecurity.md
│   └── project-management.md
│
├── categories/
│   ├── programming.md
│   ├── cloud.md
│   ├── research.md
│   ├── ai.md
│   ├── security.md
│   └── soft-skills.md
│
├── assignments/
│
└── resources/
```

---

# Learning Model

The learning model consists of four layers:

```text
Course Catalog
        ↓
Learning Paths
        ↓
Practical Assignments
        ↓
Project Contributions
```

Contributors first complete structured learning before participating in project work.

---

# Course Catalog

All available courses are maintained in:

```
COURSE_CATALOG.md
```

Each course includes:

- Course ID
- Category
- Provider
- Description
- Difficulty Level
- Duration
- Prerequisites
- Learning Resources

Example:

| Course ID | Course Name |
|------------|-------------|
| GIT-001 | Git Fundamentals |
| PY-001 | Python Programming |
| RES-001 | Research Methodology |

---

# Learning Paths

Learning paths define the recommended sequence of courses for a particular role or project.

Examples include:

- Foundation
- Research
- AI Agents
- FaaS
- DevOps
- Cybersecurity

Each learning path references Course IDs from the Course Catalog.

---

# Practical Assignments

Every learning path should include practical exercises.

Assignments are designed to verify that contributors can apply what they have learned.

Examples:

- Git workflow
- Pull Request creation
- Documentation updates
- Python exercises
- Linux administration
- API implementation

---

# Resources

Additional learning resources include:

- Books
- Official documentation
- Articles
- Videos
- Certification references
- Glossary of technical terms

---

# Repository Usage

This repository serves as the learning resource for other repositories.

Example:

```text
interns
        │
        ├── Assign GIT-001
        ├── Assign SDLC-001
        └── Track completion

research-template
        │
        ├── Assign RES-001
        └── Assign DOC-001

faas-platform
        │
        ├── Assign FAAS-001
        ├── Assign DOCKER-001
        └── Assign NETWORK-001
```

Course completion should be tracked in the respective project or program repository, not in this repository.

---

# Who Can Use This Repository?

This repository is intended for:

- Interns
- Research Scholars
- Open Source Contributors
- Software Engineers
- Technical Mentors
- Community Members

---

# Contributing

We welcome contributions that improve learning resources.

Examples include:

- New technical courses
- Updated learning paths
- Practical assignments
- Books and articles
- Reference materials
- Documentation improvements

Please refer to **CONTRIBUTING.md** before submitting changes.

---

# Guiding Principles

- Learn Continuously
- Share Knowledge
- Practice Before Production
- Document Everything
- Contribute Back to the Community

---

# Related Repositories

| Repository | Purpose |
|------------|---------|
| interns | Training management, evaluations, and contributor profiles |
| research-template | Research project support and academic collaboration |
| Project Repositories | Real-world software development and open-source contributions |

---

# Vision

To build a centralized learning ecosystem that enables contributors to develop technical skills, gain real-world experience, and confidently contribute to research, open-source projects, and modern software engineering initiatives.
