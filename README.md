# 🚀 Static Website CI/CD Pipeline

This project demonstrates a **CI/CD pipeline for deploying a static website (HTML & CSS)** using GitHub Actions.

---

## 📌 Project Overview

This project automates the process of building and deploying a static website.
Whenever code is pushed to the repository, the CI/CD pipeline:

* Validates the code
* Packages the website files
* Deploys them automatically to GitHub Pages

---

## 🔄 Workflow

```text
Git Push → GitHub Actions → Upload Artifact → Deploy → Live Website
```

---

## ⚙️ Tech Stack

* Git & GitHub
* GitHub Actions (CI/CD)
* GitHub Pages (Hosting)
* HTML, CSS

---

## 📁 Project Structure

```
.
├── index.html
├── style.css
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## 🚀 CI/CD Pipeline

The pipeline is defined in:

```
.github/workflows/deploy.yml
```

### Key Steps:

1. **Checkout Code**
2. **Configure GitHub Pages**
3. **Upload Artifact**
4. **Deploy to GitHub Pages**

---

## 🔐 Permissions Used

```yaml
permissions:
  contents: read
  pages: write
  id-token: write
```

---

## 🌐 Live Demo

👉 https://monalisa0311.github.io/static-page-deploy/

---

## 🧠 Key Learnings

* CI/CD pipeline setup using GitHub Actions
* Artifact-based deployment strategy
* Role of permissions in workflows
* Debugging workflow failures
* Difference between deploy strategies

---

## ⚡ How to Use

1. Clone the repository
2. Make changes to HTML/CSS files
3. Push changes to `main` branch

```bash
git add .
git commit -m "update"
git push
```

👉 The site will automatically update after deployment

---

## 🎯 Future Enhancements

* Add JavaScript support
* Convert to React application
* Dockerize the application
* Deploy to AWS S3 + CloudFront

---

