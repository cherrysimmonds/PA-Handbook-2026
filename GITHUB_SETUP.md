# How to Push to GitHub

Your app is ready! Follow these steps to create a GitHub repository and publish it.

---

## Step 1 — Create a GitHub account (if you don't have one)
Go to https://github.com and sign up for a free account.

---

## Step 2 — Create a new repository on GitHub

1. Click the **+** button (top right) → **New repository**
2. Name it: `pa-handbook-chatbot`
3. Leave it **Public** (required for free GitHub Pages hosting)
4. Do **NOT** tick "Add a README file"
5. Click **Create repository**

---

## Step 3 — Push your code

GitHub will show you setup instructions. Copy and run the commands below in your Terminal (Mac) or Command Prompt (Windows) from inside this folder:

```bash
# Navigate to the project folder (adjust path to match yours)
cd "AI week 8 Capstone Project/pa-handbook-chatbot"

# Initialise git and push
git init
git config user.email "chessimmonds@gmail.com"
git config user.name "Cherry Simmonds"
git branch -m main
git add .
git commit -m "Initial commit: PA Handbook Q&A chatbot"
git remote add origin https://github.com/YOUR-USERNAME/pa-handbook-chatbot.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

---

## Step 4 — Enable GitHub Pages (free hosting!)

1. On your repository page, click **Settings**
2. Click **Pages** in the left sidebar
3. Under "Branch", select **main** and **/ (root)**
4. Click **Save**

After a minute or two, your app will be live at:
```
https://YOUR-USERNAME.github.io/pa-handbook-chatbot/
```

Share this link with your team!

---

## Need help?

Contact Independent Lives: info@independentlives.org | 01903 219482
