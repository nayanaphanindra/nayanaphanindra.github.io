# Nayana Phanindra — Portfolio Site

Personal portfolio and blog for Nayana Phanindra, Instructional Designer based in Bangalore, India.

Built with [Jekyll](https://jekyllrb.com/) · Hosted on [GitHub Pages](https://pages.github.com/)

---

## Quick Start

**Read `SETUP_GUIDE.md` first** — it has full step-by-step instructions for setting up GitHub Pages from scratch.

---

## Adding Content

### New Blog Post
Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`:
```yaml
---
layout: post
title: "Your Post Title"
date: 2025-03-10
category: Learning Design
read_time: 5
excerpt: "Short summary shown in blog list."
---

Your content here in Markdown.
```

### New Portfolio Item
Create a file in `_portfolio/` named `your-project.md`:
```yaml
---
layout: portfolio_item
title: "Project Title"
type: "E-Learning · Articulate Storyline"
tools: "Articulate Storyline 360"
year: "2024"
excerpt: "One sentence describing the project and outcome."
---

Your case study here in Markdown.
```

### Update Experience
Edit `_data/experience.yml`

### Update Skills
Edit `_data/skills.yml`

### Update Qualifications
Edit `qualifications.html` directly

---

## Site Structure

```
nayana-portfolio/
├── _config.yml          ← Site settings (name, email, URL)
├── index.html           ← Homepage (all sections)
├── qualifications.html  ← Qualifications page
├── _layouts/            ← Page templates
├── _data/
│   ├── experience.yml   ← Work history
│   └── skills.yml       ← Skills by category
├── _posts/              ← Blog posts (YYYY-MM-DD-title.md)
├── _portfolio/          ← Portfolio items
├── assets/
│   ├── css/main.scss    ← All styles
│   └── images/          ← Put your photo here
├── blog/index.html      ← Blog listing page
├── portfolio/index.html ← Portfolio listing page
└── SETUP_GUIDE.md       ← Full setup instructions
```

---

*© Nayana Phanindra*
