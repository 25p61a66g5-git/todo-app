# My Tasks (React + Vite todo app)

## Run locally
```
npm install
npm run dev
```
Open http://localhost:5173/

## Push to GitHub (user: 25p61a66g6-git)
1. On github.com create a NEW EMPTY repository named `todo-app` (no README, no .gitignore).
2. In this folder run:
```
git init
git add .
git commit -m "Todo app"
git branch -M main
git remote add origin https://github.com/25p61a66g6-git/todo-app.git
git push -u origin main
```

## Publish the website (GitHub Pages)
```
npm run deploy
```
Then open: https://25p61a66g6-git.github.io/todo-app/
(If it shows 404 at first, wait 1-2 minutes. Also check Repo -> Settings -> Pages -> Source = "Deploy from a branch", branch `gh-pages`, folder `/ (root)`.)
