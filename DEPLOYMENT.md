# How to Put Your Website Online (Free)

Since I cannot access your personal accounts, here is the fastest way to put your site online for free.

## Option 1: Netlify Drop (Easiest - No Account Required initially)

1.  Open [Netlify Drop](https://app.netlify.com/drop).
2.  Open your file explorer on your computer.
3.  Locate the folder containing your project files (`index.html`, `style.css`, etc.).
4.  **Drag and drop** the entire folder into the box on the Netlify page.
5.  Wait a few seconds. Netlify will give you a live URL (e.g., `https://random-name-12345.netlify.app`).
6.  You can now share this link with anyone!

## Option 2: GitHub Pages (Best for long term)

1.  Create a repository on [GitHub.com](https://github.com).
2.  Push your code to the repository (I have already initialized Git for you).
    ```bash
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin <YOUR_GITHUB_REPO_URL>
    git push -u origin main
    ```
3.  Go to your Repository Settings > Pages.
4.  Select "Deploy from a branch" and choose `main`.
5.  Save. Your site will be online at `https://<username>.github.io/<repo-name>`.
