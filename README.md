<img width="428" height="210" alt="image" src="https://github.com/user-attachments/assets/85851339-ba85-40fb-aecd-ea06d7f10548" />

**Live site:** https://copilot-founder.github.io/git-training/

**Clone Repo url:** https://github.com/copilot-founder/git-training/

## Git Training Content

### Event Invitation
- Event invitation design image included

### Interactive Practice
- **No Git CLI installation required!**
- Practice link: https://copilot-founder.github.io/gitlearn/

### Training Agenda (55 minutes total)
- **5 Min** — Welcome & Introduction
- **10 Min** — GitHub Basics & Branching, Merging, Pull Requests
- **20 Min** — Hands-On Exercises - Live
- **5 Min** — Cheat Sheet
- **15 Min** — Q&A and Wrap-Up

## 🔧 Automatic Deployment

This repository uses **GitHub Actions** for automatic deployment:

### Setup Steps:
1. **Push your changes:**
   ```bash
   git add .
   git commit -m "Update training materials"
   git push
   ```

2. **Enable GitHub Pages:**
   - Go to repository **Settings** → **Pages**
   - Source: **GitHub Actions**
   - The workflow will automatically deploy on every push

3. **Workflow Features:**
   -  Automatic deployment on push to main/master
   -  Proper permissions for Pages deployment
   -  Artifact upload and deployment
   -  No Jekyll processing (static HTML)

### Manual Deployment (if needed):
- Go to **Actions** tab in your repository
- Click **"Deploy GitHub Training Site"**
- Click **"Run workflow"**

## 📁 Repository Structure
```
git-training/
├── .github/workflows/
│   └── deploy.yml          # Auto-deployment workflow
├── index.html              # Beautiful documentation site
├── GitHub-event-invitation.jpeg
├── .nojekyll              # Prevents Jekyll processing
├── .gitignore
├── LICENSE
└── README.md
```

## Contributing
Feel free to fork and contribute to this repository!

---

### Thank you for reaching this repository!
### H a p p y    L e a r n i n g
### @mohitmehral
