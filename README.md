# You Won't Get It

A personal blog. Not for you.

## One-time setup

### 1. Install Hugo

```bash
brew install hugo
```

### 2. Clone this repo and add the theme

```bash
git clone https://github.com/YOUR_USERNAME/youwontgetit.git
cd youwontgetit
git submodule add https://github.com/clente/hugo-bearcub.git themes/hugo-bearcub
```

### 3. Update `hugo.toml`

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username in the `baseURL` line.

### 4. Enable GitHub Pages

In your repo on GitHub:
- Go to **Settings → Pages**
- Under **Source**, select **GitHub Actions**

### 5. Push

```bash
git add .
git commit -m "init"
git push
```

The GitHub Action will build and deploy automatically. Your site will be live at:
`https://YOUR_USERNAME.github.io/youwontgetit/`

---

## Writing a new post

Option A — just create a file:
```bash
# Create a new markdown file in content/posts/
# Use Typora, iA Writer, or whatever you like
```

Option B — use Hugo's scaffolding:
```bash
hugo new posts/whatever-thought.md
```

Then edit the file, and:
```bash
git add .
git commit -m "thought"
git push
```

That's it. Live in ~30 seconds.

## Local preview

```bash
hugo server -D
# → http://localhost:1313/youwontgetit/
```

## Theme

[hugo-bearcub](https://github.com/clente/hugo-bearcub) — deliberately minimal, text-first, no JavaScript, no tracking.
