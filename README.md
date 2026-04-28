# Single Page CV — Documentation

> **Project:** Single Page CV
> **Part of:** [roadmap.sh Frontend Series](https://roadmap.sh/projects/single-page-cv)
> **Author:** Anubhav Singh

---

## Project Overview

A semantic, SEO-optimised single-page CV built with pure HTML. No CSS, no JavaScript — just well-structured HTML that serves as the foundation for a personal resume hosted on the web.

---

## File Structure

```
single-page-cv/
├── index.html        # Main CV page
├── assets/
│   └── my_icon.ico   # Favicon
└── README.md         # Project documentation
```

---

## Features

### 1. Semantic HTML
The page uses meaningful HTML5 elements instead of generic `<div>` tags, making the content accessible and machine-readable.

| Element | Purpose |
|---|---|
| `<main>` | Wraps the entire CV content |
| `<header>` | Contains personal identity and contact info |
| `<section>` | Groups related content (Skills, Education, Experience, Connect) |
| `<article>` | Wraps each individual work experience entry |
| `<address>` | Marks up contact/location information |
| `<ul>` / `<li>` | Lists for skills, bullet points, and links |
| `<strong>` | Highlights key terms and technologies |
| `<a>` | External links to profiles |

### 2. SEO Meta Tags
Essential meta tags are included in `<head>` to help search engines understand and index the page.

```html
<meta name="description" content="Personal portfolio site">
<meta name="keywords"    content="Personal portfolio site">
<meta name="author"      content="Anubhav Singh">
<title>Anubhav Singh - Software Engineer</title>
```

| Tag | Purpose |
|---|---|
| `description` | Summary shown in Google search results |
| `keywords` | Hints to search engines about page topics |
| `author` | Credits the page creator |
| `title` | Appears in browser tab and search result headings |

### 3. Open Graph (OG) Tags
OG tags control how the page looks when shared on social media platforms like LinkedIn, WhatsApp, and Facebook.

```html
<meta property="og:title"       content="Anubhav Singh - Software Engineer">
<meta property="og:description" content="Personal portfolio site">
<meta property="og:type"        content="website">
<meta property="og:url"         content="https://yoursite.com">
<meta property="og:image"       content="https://yoursite.com/preview.png">
```

| Tag | Purpose |
|---|---|
| `og:title` | Title shown in the social media link card |
| `og:description` | Short description below the title |
| `og:type` | Type of content (`website`, `article`, etc.) |
| `og:url` | Canonical URL of the page |
| `og:image` | Preview image shown when the link is shared |

### 4. Favicon
A favicon is included so the CV page has a custom icon in the browser tab.

```html
<link rel="shortcut icon" href="assets/my_icon.ico" type="image/x-icon">
```

---

## Page Sections

### Header — Personal Info
Name, job title, location, phone number, and email address.

### Skills
Categorised list of technical skills across Languages, Android, Backend, and Tools.

### Education
Degree, institution, duration, and relevant coursework.

### Experience
Two internship roles, each as a standalone `<article>`:
- **Stealth AI Start-up** — Android Developer Intern *(July 2025 – Oct 2025)*
- **Adgama Digital Pvt. Ltd.** — SDE Intern *(Sept 2024 – Jan 2025)*

### Connect
Links to GitHub, LeetCode, LinkedIn, Codeforces, and CodeChef profiles.

---

## How to Run

No build tools or dependencies required.

1. Clone or download the project folder.
2. Open `index.html` in any web browser.

```bash
# Or use VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

---

## Project Reference

- **Challenge:** https://roadmap.sh/projects/single-page-cv
- **Roadmap:** https://roadmap.sh/frontend
