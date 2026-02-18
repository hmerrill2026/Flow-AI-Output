# Push this project to GitHub

## 1. Install Git (if you haven’t)

- Go to **https://git-scm.com** and download for Windows.
- Run the installer (defaults are fine).
- Restart Cursor after installing.

## 2. Create a new repo on GitHub

1. Go to **https://github.com** and sign in.
2. Click the **+** (top right) → **New repository**.
3. **Repository name:** e.g. `spend-sankey` (no spaces).
4. **Public**.
5. **Do not** check “Add a README” or “Add .gitignore”.
6. Click **Create repository**.

## 3. Push from Cursor

Open the terminal in Cursor (**Ctrl + `**).  
Make sure you’re in this project folder (e.g. **File → Open Folder → Sankey Chart**).

Run these **one at a time** (replace `YOUR_USERNAME` and `spend-sankey` with your GitHub username and repo name):

```powershell
git init
```

```powershell
git add .
```

```powershell
git commit -m "Initial commit: Spend Sankey app"
```

```powershell
git branch -M main
```

```powershell
git remote add origin https://github.com/YOUR_USERNAME/spend-sankey.git
```

```powershell
git push -u origin main
```

When you run `git push`, a browser or popup may ask you to sign in to GitHub (or use a Personal Access Token). Do that once; after that, push will work from the terminal.

## 4. Share

Your repo URL will be: **https://github.com/YOUR_USERNAME/spend-sankey**  
Send that link so others can clone or download the project.
