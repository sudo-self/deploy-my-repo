# 🚀 deploy-my-repo

**deploy-my-repo** is a simple tool to generate **one-click deploy buttons** for your GitHub repositories. Supports platforms like **Vercel**, **Cloudflare Workers**, **Netlify**, and **CodeSandbox**.

👉 Live Demo: [https://deploy-my-repo.vercel.app](https://deploy-my-repo.vercel.app)

---

## ✨ Features

- Generate deploy buttons by entering just your GitHub username and repo name.
- Supports:
  - Vercel
  - Cloudflare Workers
  - Netlify
  - CodeSandbox
- Export generated buttons as embeddable HTML.
- Built with HTML, TailwindCSS, and Vanilla JS.

---

## 📦 How to Use

1. **Visit the Site**
   Open [deploy-my-repo.vercel.app](https://deploy-my-repo.vercel.app) in your browser.

2. **Enter Details**
   - GitHub Username: `your-username`
   - Repository Name: `your-repo`

3. **Click "Make Buttons"**
   This generates buttons for supported platforms.

4. **Copy or Export HTML**
   - You can export the buttons as reusable HTML.
   - Use them in your project README, website, or docs.

---

## 💻 Example Output

After filling in `username: sudo-self` and `repo: deploy-my-repo`, you'll see buttons like:

<a href="https://vercel.com/new/git/sudo-self/deploy-my-repo">
  <img src="https://vercel.com/button" alt="Deploy with Vercel">
</a>

## Embed the button generator in your project docs or website


```
<script src="https://sudo-self.github.io/deploy-my-repo/deploy-my-repo.js"></script>

```
