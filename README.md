# Yuhang Wang - Personal Academic Homepage

A clean, modern academic homepage inspired by [whalexiao.github.io](https://whalexiao.github.io/).

## Quick Start (Local Preview)

Simply open `index.html` in your browser to preview.

## Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in.
2. Click **"New repository"**.
3. Name it **`<your-github-username>.github.io`** (e.g., `wangyuhang.github.io`).
4. Set it to **Public**.
5. Click **"Create repository"**.

### Step 2: Push Your Code

```bash
cd /path/to/My_Home_Page
git init
git add .
git commit -m "Initial commit: personal homepage"
git branch -M main
git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (in the sidebar).
3. Under **Source**, select **Deploy from a branch**.
4. Select **main** branch, root (`/`), and click **Save**.
5. Wait 1–2 minutes, then visit `https://<your-github-username>.github.io`.

## Customization

- **Avatar**: Replace `avatar.jpg` with your own photo (recommended 400x400px).
- **Links**: Update GitHub, Google Scholar URLs in `index.html`.
- **Content**: Edit the HTML sections to update your information.
- **Colors**: Modify CSS variables in `style.css` under `:root`.

## Project Structure

```
My_Home_Page/
├── index.html      # Main HTML page
├── style.css       # Stylesheet
├── avatar.jpg      # Your photo (add your own)
└── README.md       # This file
```
