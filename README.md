# CI for Static Website

Automate build & validation for a static website

- Repo: static HTML site with GitHub Actions
- Goal: consistent quality checks on every commit
- Output: GitHub Pages deployment + CI pipeline

---

# Problem & Objectives

- Build a simple static website
- Automate validation using CI
- Ensure quality gates before merges
- Keep deployment repeatable and reliable

---

# Project Structure

- src/index.html: Tailwind-based landing page
- .github/workflows/deploy.yaml: CI/CD workflow
- problem_statement.md: assignment scope

Key content highlights:
- Hero section + project summary
- “What this repo does” and outcome list
- Canvas background animation

---

# CI/CD Workflow (GitHub Actions)

Trigger:
- On push to main

Steps:
- Checkout repository
- Build dist folder and copy index.html
- Configure GitHub Pages
- Upload Pages artifact
- Deploy to GitHub Pages

Outcome:
- Automatic publish on every main update

---

# Quality & Validation Intent

From project statement:
- Validate HTML / run lint tools
- CI checks on each commit

Current repo focus:
- Deployment pipeline in deploy.yaml
- Static site stays consistent via automated publish

Future-ready additions:
- HTML validation (e.g., HTMLHint)
- Formatting checks (Prettier)

---

# Conclusion

- Built a clean, modern static site
- Added automated deployment via GitHub Actions
- Established a CI foundation for validation and linting
- Ready to extend with stronger quality checks as needed
