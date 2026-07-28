# My Web App

4 alag projects ko merge karke banaya gaya ek static web app:

| File | Kya hai |
|---|---|
| `index.html` | Home page — sab apps ke links |
| `alarm.html` | Alarm Clock (React, CDN se load hota hai) |
| `calculator.html` | Scientific Calculator |
| `snake.html` | Snake Game |
| `game.html` | Dino Runner Game |

Koi build step nahi chahiye — sirf `index.html` open karo browser me, ya GitHub Pages par deploy karo.

## GitHub par upload

```bash
git init
git add .
git commit -m "Merged 4 projects into one web app"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git push -u origin main
```

## GitHub Pages se live dekhna (optional)
Repo Settings → Pages → Source: `main` branch, `/ (root)` folder → Save.
Kuch minute baad `https://USERNAME.github.io/REPO-NAME/` par live ho jayega.
