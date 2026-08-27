# 📊 Internship Progress Tracker & Bug Report

An interactive, spreadsheet-style dashboard to track QA work, bug investigations, error recreate steps, and .NET / ASP learning roadmap progress with full image proof attachments and analytics.

---

## 🚀 Live Demo on GitHub Pages
Once deployed, your live application is available at:
`https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## ✨ Features

- **🖼️ Image & Screenshot Attachment Support**:
  - **Drag & Drop / File Picker**: Upload multiple screenshots per task.
  - **Clipboard Paste (`Ctrl+V`)**: Instant screenshot pasting directly from clipboard.
  - **External Image URL**: Link to web hosted assets.
  - **Fullscreen Lightbox**: Interactive high-res image modal with navigation and download button.
  - **Thumbnail Gallery**: Inline table previews with hover zoom.
- **💾 LocalStorage Persistence**:
  - All user additions, image attachments, edits, status updates, and deletions automatically save to your browser's `localStorage`.
- **📊 Real-time Analytics & Charts**:
  - Category completion progress bars and status distribution doughnut charts via Chart.js.
- **📋 Export & Interoperability**:
  - **Copy for Google Sheets**: 1-click clipboard export in TSV format to paste directly into Google Sheets with formatted columns.
  - **Export CSV**: Download report as `.csv` file.
- **✏️ Interactive Management**:
  - Real-time search, category filter, status filter, and image filter.
  - Inline progress % and status controls.
  - Modal editor for full updates to existing rows.

---

## 🛠️ GitHub Pages Deployment Guide

### Option 1: Automated Deployment via GitHub Actions (Configured)
1. Initialize git and commit your files:
   ```bash
   git init -b main
   git add .
   git commit -m "feat: internship tracker with image support & github pages deployment"
   ```
2. Link to your GitHub repository:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, select **GitHub Actions**
   - The included `.github/workflows/deploy.yml` workflow will automatically build and publish your site!

### Option 2: Direct Branch Deployment
- Under **Settings** > **Pages**, choose **Deploy from a branch** -> branch `main` -> folder `/ (root)`.
