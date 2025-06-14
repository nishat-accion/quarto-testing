# 📚 Quarto Documentation Projects

This repository contains multiple documentation projects built using [Quarto](https://quarto.org/). Each project is independently structured and published using GitHub Pages.

## 🔗 Live Documentation Links

| Project        | Description                         | Live URL                                                                 |
|----------------|-------------------------------------|--------------------------------------------------------------------------|
| Node.js Auth   | Node.js authentication workflow     | [View Docs 🔐](https://nishat-accion.github.io/quarto-testing/node-auth/) |
| React Login    | React login UI & state management   | [View Docs ⚛️](https://nishat-accion.github.io/quarto-testing/react-login/) |

## 📦 Folder Structure

```bash
quarto-testing/
├── node-auth/
│ ├── index.qmd
│ ├── _quarto.yml
│ └── docs/ ← generated after rendering
├── react-login/
│ ├── index.qmd
│ ├── _quarto.yml
│ └── docs/ ← generated after rendering
└── docs/
├── node-auth/
│ └── index.html
└── react-login/
└── index.html
```


## 🚀 How to View Locally

```bash
cd node-auth
quarto preview

# or

cd react-login
quarto preview
```

📤 How to Publish to GitHub Pages

1. Render each project:

```bash
quarto render
```

2. Copy each subproject's docs/ into the root-level docs/ directory:

```bash
my-repo/docs/node-auth/
my-repo/docs/react-login/
```

3. Commit and push changes:

```bash
git add .
git commit -m "Update rendered docs"
git push
```

4. GitHub Pages will serve them from:

```bash
https://nishat-accion.github.io/quarto-testing/
```
