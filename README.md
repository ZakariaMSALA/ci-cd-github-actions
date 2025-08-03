# 🚀 CI/CD Pipeline with GitHub Actions

This repository demonstrates a professional CI/CD pipeline setup for a Node.js application using GitHub Actions.

## 📦 Project Structure

```
ci-cd-github-actions/
├── app/
│   ├── index.js          # Simple Express.js app
│   └── package.json      # Start, test, lint scripts
└── .github/
    └── workflows/
        └── ci.yml        # GitHub Actions pipeline
```

## 🔁 Pipeline Overview

The CI pipeline is triggered on:
- Push to `main` branch
- Pull requests to `main`

It performs the following steps:
1. Checkout the repository
2. Set up Node.js
3. Install dependencies
4. Run lint checks
5. Run tests
6. Confirm successful build

## 🛠️ Technologies Used

- **Node.js** with **Express**
- **GitHub Actions** for CI/CD
- (Optional in future: Docker, Terraform, deployment scripts...)

## ✅ How to Run Locally

```bash
# Navigate to the app directory
cd app

# Install dependencies
npm install

# Start the app
npm start

# Run tests
npm test
```

Then open your browser at: [http://localhost:3000](http://localhost:3000)

## 📊 CI Status

![CI](https://github.com/zakaria-devops/ci-cd-github-actions/actions/workflows/ci.yml/badge.svg)

## 💼 Author

**Zakaria Msala**  
Freelance DevOps Engineer | CI/CD | Cloud | Automation  
📫 [LinkedIn](https://www.linkedin.com/in/zakaria-msala-86758788/) – [GitHub](https://github.com/zakaria-devops)

---

> Want to work with me? I'm available for freelance DevOps missions – 100% remote.
