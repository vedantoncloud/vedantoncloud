# 🚀 Complete Setup & Deployment Guide for @vedantoncloud

This guide walks you step-by-step through setting up your GitHub profile so that it matches and surpasses elite developer profiles like **ishandutta2007**.

---

## 📌 Step 1: Create Your GitHub Special Profile Repository

GitHub provides a special feature: when you create a public repository with the **exact same name as your GitHub username**, the `README.md` in that repository is displayed prominently at the top of your personal GitHub profile page (`https://github.com/vedantoncloud`).

1. Go to **[GitHub New Repository](https://github.com/new)**.
2. Set **Repository name** to: `vedantoncloud`
   *(GitHub will show a banner saying: "You found a secret! `vedantoncloud/vedantoncloud` is a ✨special ✨ repository that you can use to add a README.md to your GitHub profile.")*
3. Make sure it is set to **Public**.
4. Check **Add a README file** (or leave it unchecked if you are pushing from your machine).
5. Click **Create repository**.

---

## 📌 Step 2: Push the Files Using Git (or via GitHub Web)

All files have been prepared and generated in your local workspace at:
`C:\Users\vedan\.gemini\antigravity\scratch\vedantoncloud`

### Option A: Using Git CLI (Recommended)
Open PowerShell or your terminal in `C:\Users\vedan\.gemini\antigravity\scratch\vedantoncloud` and run:

```bash
git init
git branch -M main
git add .
git commit -m "feat: launch elite cloud and devops profile readme"
git remote add origin https://github.com/vedantoncloud/vedantoncloud.git
git push -u origin main
```

*(If you already created the repo with a default README on GitHub, you can use `git push -u origin main --force` or pull first).*

### Option B: Using GitHub Web Interface
1. Open the repository on GitHub: `https://github.com/vedantoncloud/vedantoncloud`.
2. Edit `README.md` and copy-paste the entire contents of `C:\Users\vedan\.gemini\antigravity\scratch\vedantoncloud\README.md`.
3. Create the file `.github/workflows/snake.yml` and paste the contents of `snake.yml`.
4. Commit the changes.

---

## 📌 Step 3: Enable Permissions for the Snake Animation

The contribution snake runs on a scheduled GitHub Action and pushes the animation SVG to an `output` branch.

1. In your `vedantoncloud/vedantoncloud` repository, click **Settings** (top tabs).
2. On the left sidebar, click **Actions** ➔ **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Check **Allow GitHub Actions to create and approve pull requests**.
6. Click **Save**.
7. Now click the **Actions** tab at the top of your repository.
8. Click **Generate Snake Animation** on the left menu.
9. Click **Run workflow** ➔ **Run workflow**.
   *(It will run in ~30 seconds, generate `dist/github-contribution-grid-snake.svg`, and push it to the `output` branch).*

---

## 📌 Step 4: Optimize Your GitHub Profile Sidebar & Settings

To ensure your profile looks 100% polished to recruiters and tech leads:

1. Go to **[GitHub Profile Settings](https://github.com/settings/profile)**.
2. **Name**: `Vedant Mishra`
3. **Bio**:
   ```
   Cloud & DevOps Engineer ☁️ | AWS & OCI Certified | Building CloudForge & CI/CD Pipelines 🚀
   ```
4. **Company / Affiliation**: `MIT ADT University | Ex-HEPro AI`
5. **Location**: `Pune, India`
6. **Website URL**: `https://vedantoncloud.github.io`
7. **Social Accounts**:
   - LinkedIn: `https://www.linkedin.com/in/vedant-mishra-8b3987328/`
   - Docker Hub: `https://hub.docker.com/u/vedantoncloud`
   - Email: `vedantmanikmishra@gmail.com`

---

## 📌 Step 5: Pin Your Top 6 Repositories

On your main profile page (`https://github.com/vedantoncloud`), click **Customize your pins** and select:

1. **`Cloudforge`** (Mini Platform as a Service)
2. **`myapp`** (End-to-End DevOps CI/CD Pipeline)
3. **`CC-Prediction-Bot`** (AWS Cloud Cost Prediction Bot)
4. **`CloudOps-AI`** (Cloud Operations & AI Integration)
5. **`vedantoncloud.github.io`** (Personal Portfolio)
6. **`cycra-health-trajectory`** (Web Application & Telemetry)

---

## 🌟 What Makes This Profile Stand Out (vs. ishandutta2007)

| Feature | Ishan Dutta's Profile | Your Custom Profile (`vedantoncloud`) |
| :--- | :--- | :--- |
| **Theme & Aesthetic** | Dark minimal / AI focus | Cloud & DevOps Dark Cyan / Electric Blue Gradient |
| **Interactive Header** | Static / Standard text | Animated Dynamic Capsule Header + Live Typing SVG |
| **Domain Categorization**| General programming | Tailored Cloud & DevOps Arsenal (AWS, OCI, Docker, CI/CD, FinOps) |
| **Project Showcase** | Basic links | Structured 2x2 Feature Matrix with Tech Badges & Impact |
| **Dynamic Analytics** | Stats Cards | Full GitHub Stats + Top Languages + Streak Stats + Activity Graph |
| **Gamified Elements** | Contribution Graph | Automated Snake Eating Contributions (`platane/snk`) |
| **Certifications** | Text list | Clean Credential Verification Table (AWS & Oracle Certified) |
