#  DevOps Project: Version-Controlled Workflow using Git & GitHub

##  Overview
This project demonstrates how to manage a DevOps project using **Git best practices** — including proper branching, pull requests, tagging, and documentation.  
It is part of a larger series of tasks showcasing DevOps automation and CI/CD implementation.

---

##  Features
- Git repository with structured branching model  
- Pull requests for merging and collaboration  
- Markdown-based documentation for each task  
- Tagged releases for version tracking  
- `.gitignore` configured for clean commits  

---

##  Branching Strategy

| Branch | Purpose |
|--------|----------|
| **main** | Stable, production-ready code |
| **dev** | Integration and testing branch |
| **feature/** | Feature-specific branches (e.g., `feature`) |

Example commands:
```bash
git checkout -b dev
git push -u origin dev

git checkout -b feature
git add .
git commit -m "Added login feature script"
git push -u origin feature

