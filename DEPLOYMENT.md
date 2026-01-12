# Deployment Guide

This project is ready to be deployed via Vercel using GitHub.

## 1. Push to GitHub

The local repository has been initialized and committed.
Please run the following command in your terminal to push the code to your GitHub repository:

```bash
git push -u origin main
```

*Note: If the remote repository is not empty, you might encounter an error. In that case, you may need to pull first or force push if you intend to overwrite everything.*

## 2. Deploy on Vercel

1.  Log in to [Vercel](https://vercel.com/).
2.  Click **"Add New..."** -> **"Project"**.
3.  Import the repository `otsura-kensetsu` from your GitHub account.
4.  **Framework Preset**: Select **"Other"** (since this is a plain HTML/CSS static site).
5.  Click **"Deploy"**.

Your website will be live at a Vercel URL (e.g., `otsura-kensetsu.vercel.app`) shortly!
