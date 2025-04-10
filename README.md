# CS580 Course Site – Just the Docs Setup

This repository contains a ready-to-use course website template built with the [Just the Docs](https://just-the-docs.github.io/just-the-docs/) Jekyll theme. It is fully compatible with GitHub Pages and intended for easy customization, content structuring, and collaboration.

## 🚀 Getting Started

To use this site for your own course:

### Option 1: Use This Repository Directly
1. **Clone or Fork** this repository.
2. If forking, rename your forked repo as needed.
3. In `_config.yml`, update the following fields:
   - `title`: Your course name (e.g., "Introduction to AI")
   - `url`: Set to `https://YOUR_USERNAME.github.io`
   - `baseurl`: Set to `/your-repo-name` (or leave blank if deploying from a personal GitHub Pages site)

### Option 2: Transfer Ownership
If this site was prepared for you by someone else, they can transfer this repository to your GitHub account.
1. The original owner should go to **Settings > Danger Zone > Transfer Ownership**.
2. You will receive an invitation to accept the repository.
3. Once accepted, it will live under your GitHub account.

### Option 3: Collaborate
If you wish to co-maintain the site with the current owner:
1. Ask to be added as a **collaborator** under **Settings > Collaborators**.
2. Accept the invitation and begin editing directly.

---

## 🔧 Deploying with GitHub Pages + GitHub Actions
This repo uses **GitHub Actions** to build and deploy the site with full plugin support (e.g., `jekyll-last-modified-at`).

### GitHub Pages Setup:
1. Go to **Settings > Pages**
2. Under "Source," choose: **GitHub Actions**

The site will be deployed to: `https://YOUR_USERNAME.github.io/your-repo-name`

### ⚠️ Permission Fix (First-Time Setup)
If the GitHub Action fails with a `Permission denied to github-actions[bot]` error:
1. Go to **Settings > Actions > General**
2. Scroll to **Workflow permissions**
3. Check **"Read and write permissions"**
4. Click **Save**
5. Re-run the failed deployment workflow under the **Actions** tab.

---

## ✏️ Customizing Your Site
- `_config.yml`: General site settings and theme configuration
- `_sass/color_schemes/`: Define your own theme colors
- `index.md`, `syllabus.md`, `schedule.md`, etc.: Course content in Markdown
- `_layouts/` and `_includes/`: (Advanced) Custom layout and style changes

---

## 📄 License
Feel free to reuse and modify this template for educational purposes.

If you adapt or republish this site, please consider including a small credit such as:

> "Built using a template developed by [Juan Huang](https://github.com/radioheado)"

…anywhere that feels appropriate (e.g., footer, README, or About page).
