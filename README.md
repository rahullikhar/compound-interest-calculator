# Compound Interest Calculator

A fully deployed web app built to demonstrate a real-world DevOps workflow — containerized with Docker and automatically deployed via GitHub Actions CI/CD pipeline.

🔗 **Live Demo:** https://rahullikhar.github.io/compound-interest-calculator

---

## What This Project Does

An interactive compound interest calculator with:
- Adjustable principal, interest rate, time period and compounding frequency
- Real-time chart showing money growth year by year
- Indian currency format (₹ L / Cr)
- Fully responsive design

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript, Chart.js |
| Containerization | Docker (Nginx Alpine) |
| CI/CD Pipeline | GitHub Actions |
| Hosting | GitHub Pages |

---

## DevOps Workflow
```
Code pushed to main branch
        ↓
GitHub Actions triggered automatically
        ↓
Docker image built on GitHub's Ubuntu runner
        ↓
index.html extracted from container
        ↓
Deployed to GitHub Pages
        ↓
Live site updated in ~16 seconds
```

## Project Structure
```
compound-interest-calculator/
├── index.html                  # Frontend app
├── Dockerfile                  # Nginx container config
└── .github/
    └── workflows/
        └── deploy.yml          # CI/CD pipeline
```

---

## Key Learnings

- Wrote a `Dockerfile` using Nginx Alpine to serve a static app
- Built and ran Docker containers inside a GitHub Actions runner
- Configured a CI/CD pipeline that triggers on every push to `main`
- Debugged a failed pipeline by reading error logs and fixing deprecated action versions
- Deployed a live production URL using GitHub Pages

---

## Author

**Rahul Likhar**  
Remote Support Engineer → DevOps Engineer (in transition)  
[GitHub](https://github.com/rahullikhar) • [LinkedIn](https://www.linkedin.com/in/rahullikhar)
