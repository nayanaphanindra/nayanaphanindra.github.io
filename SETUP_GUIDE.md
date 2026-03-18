# Nayana Phanindra — Portfolio Site
## Complete Setup Guide for GitHub Pages

---

## OVERVIEW

Your site uses **Jekyll** — a tool that converts your content files into a website.
GitHub Pages runs Jekyll for you automatically. You never need to pay for hosting.

**Your site will live at:** `https://YOUR-USERNAME.github.io`

---

## STEP 1 — Create a GitHub Account

1. Go to **https://github.com**
2. Click **Sign up** (top right)
3. Choose a username — this becomes part of your URL, so pick something professional
   - Good: `nayanaphanindra`, `nayana-id`, `nayanap`
4. Complete verification and create your account

---

## STEP 2 — Create Your Repository

A "repository" (repo) is just a folder on GitHub that stores your site.

1. Once logged in, click the **+** icon (top right) → **New repository**
2. Name it exactly: `YOUR-USERNAME.github.io`
   - Example: if your username is `nayanaphanindra`, name it `nayanaphanindra.github.io`
   - ⚠️ This exact name is what makes GitHub Pages work
3. Set it to **Public**
4. Click **Create repository**

---

## STEP 3 — Upload Your Site Files

You have two options. Option A is easier for beginners.

### Option A — Upload via browser (easiest)

1. On your new empty repo page, click **uploading an existing file**
2. Drag and drop ALL the files and folders from the site package you downloaded
   - Make sure the folder structure is preserved (\_posts, \_layouts, etc.)
3. Scroll down, write a commit message like "Initial upload"
4. Click **Commit changes**

### Option B — Use GitHub Desktop (recommended for ongoing updates)

1. Download **GitHub Desktop** from https://desktop.github.com
2. Sign in with your GitHub account
3. Click **Clone repository** → find your repo → choose where to save it on your computer
4. Copy all your site files into that local folder
5. GitHub Desktop will show your changes → add a summary → click **Commit to main** → **Push origin**

---

## STEP 4 — Enable GitHub Pages

1. In your repo, click **Settings** (tab at top)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **GitHub Actions** (not "Deploy from a branch")
4. GitHub will detect the workflow file already in `.github/workflows/deploy.yml`
5. Click **Save**

The workflow automatically builds and deploys your Jekyll site every time you push changes.
Your site will be live in 2–5 minutes at `https://YOUR-USERNAME.github.io`

> **Why GitHub Actions?** It's more reliable than the basic branch deploy — it runs a full Jekyll build with all plugins, and shows you exactly what went wrong if something fails.

---

## STEP 5 — Personalise the Site

Open `_config.yml` in your repo and update these values:

```yaml
title: Nayana Phanindra
email: your-real-email@gmail.com
url: "https://nayanaphanindra.github.io"   # your actual URL
linkedin_url: "https://linkedin.com/in/your-profile"
```

Edit `_data/experience.yml` to add your real work history.
Edit `_data/skills.yml` to adjust your skills list.

**To add your photo:**
1. Save your photo as `nayana.jpg` (good quality, square or portrait crop)
2. Upload it to the `assets/images/` folder
3. In `index.html`, find this comment and uncomment the line below it:
   ```html
   <!-- <img src="{{ '/assets/images/nayana.jpg' | relative_url }}" alt="Nayana Phanindra"> -->
   ```
   Remove the `<!--` and `-->` to activate it.

---

## STEP 6 — Set Up the Contact Form (Free)

The contact form uses **Formspree** — free for up to 50 messages/month.

1. Go to **https://formspree.io** and create a free account
2. Click **New Form**, give it a name
3. Copy your **Form ID** (looks like: `xpzgdkbn`)
4. In `index.html`, find this line:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
5. Replace `YOUR_FORM_ID` with your actual form ID

---

## HOW TO WRITE A BLOG POST

1. Create a new file in `_posts/` named exactly like this:
   ```
   YYYY-MM-DD-your-post-title.md
   ```
   Example: `2025-03-10-what-is-andragogy.md`

2. Start the file with this block (called "front matter"):
   ```
   ---
   layout: post
   title: "What Is Andragogy and Why Does It Matter?"
   date: 2025-03-10
   category: Learning Theory
   read_time: 4
   excerpt: "A short summary shown in the blog list and on social shares."
   ---
   ```

3. Write your post below in plain text (Markdown):
   ```
   ## A Heading

   Your paragraph here. **Bold text** and *italic text* work like this.

   Another paragraph.
   ```

4. Save and push to GitHub. Your post appears on the site in ~1 minute.

---

## HOW TO ADD A PORTFOLIO PROJECT

1. Create a new file in `_portfolio/` (note the underscore):
   ```
   your-project-name.md
   ```

2. Start with this front matter:
   ```
   ---
   layout: portfolio_item
   title: "Compliance Training Redesign"
   type: "E-Learning · Articulate Rise"
   tools: "Articulate Rise 360"
   year: "2024"
   excerpt: "One sentence describing the project and its outcome."
   ---
   ```

3. Write your case study below. A good structure:
   - **The Challenge** — what problem were you solving?
   - **My Approach** — what frameworks, methods did you use?
   - **The Solution** — what did you build?
   - **The Outcome** — what changed? (numbers if you have them)

---

## MARKDOWN QUICK REFERENCE

| You type...        | You get...           |
|--------------------|----------------------|
| `# Heading 1`      | Large heading        |
| `## Heading 2`     | Medium heading       |
| `**bold**`         | **bold**             |
| `*italic*`         | *italic*             |
| `- item`           | Bullet point         |
| `[Link](url)`      | Clickable link       |
| `> quote`          | Blockquote           |
| `---`              | Horizontal rule      |

---

## TROUBLESHOOTING

**Site not showing up?**
- Wait 5 minutes — GitHub Pages takes time on first deploy
- Check Settings → Pages → is the source set correctly?
- Make sure your repo is named exactly `username.github.io`

**Changes not appearing?**
- GitHub Pages rebuilds every time you push — takes ~1 minute
- Hard refresh your browser: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)

**Red X on your repo?**
- There's a build error. Click the X → Details to see what went wrong
- Most common cause: a typo in front matter (the `---` block at top of files)

---

## FUTURE UPGRADE PATH

When you're ready to invest in a custom domain:
1. Buy a domain (e.g. `nayanaphanindra.com`) for ~₹800–1200/year from Namecheap or Google Domains
2. In GitHub Pages settings, add your custom domain
3. Update `url:` in `_config.yml`
4. Your site moves to `nayanaphanindra.com` — all existing links still work

When you want a visual editor (no more file editing):
- Migrate to **WordPress.com** (free tier) or **self-hosted WordPress** with cheap hosting (~₹200/month on Hostinger)
- Your content can be copy-pasted across. The design would need to be rebuilt in a WordPress theme.

---

*Site built with Jekyll · Hosted on GitHub Pages · © Nayana Phanindra*
