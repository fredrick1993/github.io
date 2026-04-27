# Temitope Oladele Fredrick — Personal Website

**Live at:** `https://your-github-username.github.io`

---

## File Structure

```
your-username.github.io/
│
├── index.html          ← Homepage
├── research.html       ← Research, projects, publications, skills
├── posts.html          ← Posts feed (lists all posts)
├── cv.html             ← Full CV + certifications
├── contact.html        ← Contact form + links
│
├── assets/
│   ├── style.css       ← Shared styles (don't edit unless you know CSS)
│   ├── shared.js       ← Shared JavaScript (nav, animations, canvas)
│   └── photo.png       ← Your profile photo
│
└── posts/
    ├── post-template.html   ← COPY THIS for every new post
    ├── post-001.html        ← First post
    ├── post-002.html        ← Second post
    └── post-003.html        ← Third post
```

---

## How to Add a New Post (Weekly)

### Step 1 — Copy the template
Copy `posts/post-template.html` and rename it.

Use this naming format: `post-004.html`, `post-005.html`, etc.

### Step 2 — Edit the file
Open your new file and look for the ✏️ EDIT markers. Change:

| What to edit | Where to find it |
|---|---|
| Page title | `<title>POST TITLE HERE...</title>` |
| Post date | `<span class="post-date">MONTH DD, YYYY</span>` |
| Read time | `<span class="post-read">X min read</span>` (words ÷ 200) |
| LinkedIn badge | Delete the `post-src-badge` line if NOT from LinkedIn |
| Post title (big heading) | `Your Post Title Goes Here` |
| One-line excerpt | The sentence under the title |
| Tags | Replace `Tag One`, `Tag Two` with your real tags |
| Post body | Replace the example content with your actual post |
| Next post link | Uncomment the next post button, update the filename |

### Step 3 — Add it to the posts feed
Open `posts.html` and find the comment:
```html
<!-- ADD NEW POSTS ABOVE THIS LINE -->
```

Copy one of the existing post card blocks above it and update:
- `href="posts/post-XXX.html"` — your new filename
- `data-cat="..."` — category tags (research, bioinformatics, linkedin, career)
- The date, title, excerpt, and tags

### Step 4 — Update the homepage preview
Open `index.html` and find the Latest Posts section.
Replace the oldest post card with your new post.

### Step 5 — Upload to GitHub
Drag and drop the new post file into your GitHub repository.
Also upload `posts.html` and `index.html` since you edited those.

**The site updates automatically within 2 minutes.**

---

## How to Cross-Post from LinkedIn

1. Copy your LinkedIn post text
2. Paste it as the body content in your post file
3. Add `<span class="post-src-badge">&#128279; Originally on LinkedIn</span>` in the meta row
4. Set `data-cat="linkedin"` on the post card in `posts.html`
5. Expand the post with more detail than you could fit on LinkedIn

---

## How to Update Your Photo

1. Name your new photo `photo.png`
2. Upload it to the `assets/` folder in GitHub (replace the existing one)
3. Also open `index.html`, find `src="data:image/png;base64,..."` and replace the entire src value with `src="assets/photo.png"` — this is simpler than base64

---

## Pages at a Glance

| Page | URL | What to update |
|---|---|---|
| Homepage | `/` | Latest 3 posts, about section |
| Research | `/research.html` | When you start new projects |
| Posts | `/posts.html` | Every week (add new post card) |
| CV | `/cv.html` | When you gain new experience or certs |
| Contact | `/contact.html` | Rarely — only if details change |

---

## GitHub Pages Setup (First Time Only)

1. Create a GitHub account at github.com
2. Create a new repository — name it exactly: `your-username.github.io`
3. Set it to **Public**
4. Upload ALL the files and folders from this package
5. Go to **Settings → Pages → Source** → select `main` branch → Save
6. Wait 2 minutes → your site is live!

---

## Questions?

Email: topefred@gmail.com  
LinkedIn: linkedin.com/in/temitope-oladele-35b535196
