---
title: "ML/AI Fundamentals - Collaboration Guide"
description: "Contributing guide for ML/AI Fundamentals course content"
tableOfContents: true
sidebar:
  order: 999
---

# ML/AI Fundamentals

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/ml-ai-fundamentals/](https://siliconwit.com/education/ml-ai-fundamentals/)

Nine lessons teaching machine learning from curve fitting to deployment. Every lesson builds a working model with complete Python code. Designed for engineers who already know Python and want to understand ML, not just use it.

## Lessons

| # | Title |
|---|-------|
| 1 | What Machine Learning Actually Is |
| 2 | Linear Regression and Prediction |
| 3 | Classification: Yes or No Decisions |
| 4 | Decision Trees and Random Forests |
| 5 | How Models Learn: Gradient Descent |
| 6 | Neural Networks from Scratch |
| 7 | Practical ML with Scikit-Learn |
| 8 | Working with Real Sensor Data |
| 9 | From Training to Deployment |

## How to Contribute

All commands below work on Linux, macOS, and Windows (using Git Bash, PowerShell, or Command Prompt with Git installed).

### For Team Members (with push access)

**First time setup (clone the repo once):**

```bash
git clone https://github.com/SiliconWit/ml-ai-fundamentals.git
cd ml-ai-fundamentals
```

**Every time you start working:**

```bash
git pull origin main
```

Always pull before making changes. This avoids conflicts with other contributors.

**After making your changes:**

```bash
git add .
git commit -m "Brief description of what you changed"
git push origin main
```

**If you get a push error** (someone pushed before you):

```bash
git pull origin main
```

Git will merge the changes automatically in most cases. If there is a conflict, Git will mark the conflicting lines in the file. Open the file, choose which version to keep, then:

```bash
git add .
git commit -m "Resolve merge conflict"
git push origin main
```

**Tips to avoid conflicts:**

- Always `git pull origin main` before you start working
- Push your changes as soon as you are done, do not hold onto uncommitted work for long
- Coordinate with other contributors so two people are not editing the same file at the same time

### For External Contributors (without push access)

1. Fork the repository: [SiliconWit/ml-ai-fundamentals](https://github.com/SiliconWit/ml-ai-fundamentals)
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/ml-ai-fundamentals.git
   cd ml-ai-fundamentals
   ```
3. Make your changes and commit:
   ```bash
   git add .
   git commit -m "Brief description of what you changed"
   git push origin main
   ```
4. Open a Pull Request against `main` on the original repository
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Every lesson must contain complete, runnable Python code
- All code tested with Python 3.10+, numpy, scikit-learn, matplotlib
- No emojis, no em dashes

## License

This course content is released under the [MIT License](LICENSE).
