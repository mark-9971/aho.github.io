# aho.github.io

# Deploying Your Apple Orchard Website to GitHub Pages

This guide will walk you through deploying your simple HTML and CSS website to GitHub Pages, where it can be hosted for free.

## Prerequisites

*   A GitHub account. If you don't have one, sign up at [https://github.com/join](https://github.com/join).
*   The website files (`index.html`, `apples.html`, `ciders.html`, `activities.html`, `blog.html`, `visit.html`, and `style.css`).

## Deployment Steps

1.  **Create a New Repository on GitHub:**
    *   Log in to your GitHub account.
    *   Click the "+" icon in the top-right corner and select "New repository".
    *   Repository name: Choose a name (e.g., `apple-orchard-website` or `yourusername.github.io`).
        *   If you name it `yourusername.github.io` (replacing `yourusername` with your actual GitHub username), your site will be available at `https://yourusername.github.io`.
        *   If you use another name (e.g., `apple-orchard-website`), it will be at `https://yourusername.github.io/apple-orchard-website/`.
    *   Description: (Optional) Add a brief description.
    *   Public/Private: Select "Public". GitHub Pages for private repositories is a paid feature.
    *   Initialize this repository with: You can skip adding a README, .gitignore, or license here as we are providing the README.
    *   Click "Create repository".

2.  **Upload Your Website Files:**
    *   Once the repository is created, you'll be on the repository's main page.
    *   Click on the "Add file" button and choose "Upload files".
    *   Drag and drop all your website files (`index.html`, `apples.html`, `ciders.html`, `activities.html`, `blog.html`, `visit.html`, and `style.css`) into the upload area.
    *   Commit changes: Add a commit message (e.g., "Initial website upload").
    *   Click "Commit changes".

3.  **Enable GitHub Pages:**
    *   In your repository, go to the "Settings" tab.
    *   In the left sidebar, scroll down and click on "Pages" (under "Code and automation").
    *   Source: Under "Build and deployment", for "Source", select "Deploy from a branch".
    *   Branch:
        *   Select the branch your files are on (usually `main` or `master`).
        *   Folder: Select `/(root)`.
        *   Click "Save".

4.  **Access Your Live Website:**
    *   GitHub Pages will now build and deploy your site. This might take a minute or two.
    *   Once deployed, the URL of your live site will be displayed at the top of the GitHub Pages settings page (e.g., `https://yourusername.github.io/repository-name/`).
    *   Visit this URL in your browser to see your live website!

## Updating Your Website

To make changes:
1.  Edit your files locally on your computer.
2.  Re-upload the changed files to your GitHub repository (following Step 2, you can drag and drop to replace existing files or upload new ones).
3.  GitHub Pages will automatically rebuild and update your live website.

---

That's it! Your apple orchard website should now be live.
