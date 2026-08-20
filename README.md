# AZGUIR YASSINE — Portfolio Website

A stunning dark-green / neon hacker-aesthetic personal portfolio website, ready to deploy on GitHub Pages.

## 🚀 Features

- **Matrix rain animation** — animated Japanese/ASCII characters in the background
- **Glitch title effect** — the name glitches with cyan and red offsets
- **Typewriter effect** — cycles through developer roles
- **Scroll reveal animations** — cards and sections fade in as you scroll
- **Card tilt effect** — 3D perspective tilt on project cards
- **Responsive design** — works on all screen sizes
- **Zero dependencies** — pure HTML, CSS, JavaScript

## 📁 Files

```
index.html   — Main HTML structure
style.css    — All styles & animations
script.js    — Interactive effects & animations
```

## ✏️ How to Customize

### 1. Update your links
In `index.html`, search for `your-username` and replace with your actual usernames:
- GitHub: `https://github.com/your-username`
- LinkedIn: `https://linkedin.com/in/your-username`
- Twitter/X: `https://twitter.com/your-username`
- Instagram: `https://instagram.com/your-username`
- Email: `mailto:your-email@example.com`
- Portfolio: `https://your-portfolio-site.com`
- Indeed: `https://www.indeed.com/r/your-username`

### 2. Update your bio
Find the "Who Am I" section and replace the placeholder text.

### 3. Update your projects
Replace the 3 project cards with your real projects. Each card has:
- A project icon (emoji)
- GitHub and Live Demo links
- Title, description, and tech stack tags

### 4. Update your stats
In `index.html`, update `data-target` values on the stat numbers:
```html
<span class="stat-number" data-target="10">0</span>  <!-- Projects -->
<span class="stat-number" data-target="500">0</span> <!-- Commits -->
<span class="stat-number" data-target="15">0</span>  <!-- Repos -->
```

### 5. Update the typewriter phrases
In `script.js`, update the `phrases` array:
```js
const phrases = [
  'Your Role Here',
  'Another Role',
  ...
];
```

## 🌐 Deploy to GitHub Pages

1. Create a new GitHub repository named `your-username.github.io`
2. Push these files to the `main` branch
3. Go to Settings → Pages → Source → `main` branch
4. Your site will be live at `https://your-username.github.io` 🎉
