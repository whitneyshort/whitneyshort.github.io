# Personal Academic Website

A clean, professional multi-page static site for GitHub Pages.

## Pages

| File | Page |
|---|---|
| `index.html` | About / Bio |
| `research.html` | Research & Publications |
| `teaching.html` | Teaching |
| `outreach.html` | Outreach & Community |
| `tutoring.html` | Tutoring Services |
| `cv.html` | Curriculum Vitae |
| `style.css` | Shared stylesheet |

---

## Deployment to GitHub Pages

### 1. Create a GitHub repository

Name it `yourusername.github.io` (replace with your actual GitHub username).
This will make your site available at `https://yourusername.github.io`.

Alternatively, use any repo name and enable Pages under **Settings → Pages**;
your site will be at `https://yourusername.github.io/reponame`.

### 2. Upload files

Upload all files (`index.html`, `research.html`, `teaching.html`,
`outreach.html`, `tutoring.html`, `cv.html`, `style.css`) to the **root** of the repository.

### 3. Enable GitHub Pages

Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` → folder: `/ (root)`.

Save. Your site will be live within ~1 minute at `https://yourusername.github.io`.

---

## Customization Checklist

- [ ] Replace `Your Name` / `YN` initials everywhere
- [ ] Update the `<title>` tags in each HTML file
- [ ] Fill in your email address (`you@university.edu`)
- [ ] Update GitHub / Scholar links in `index.html`
- [ ] Add a profile photo: place `photo.jpg` in the root and follow the comment in `index.html`
- [ ] Upload your CV as `cv.pdf` (the CV page will embed it automatically)
- [ ] Fill in publications, courses, outreach activities
- [ ] Update tutoring rates on `tutoring.html`
- [ ] Update the year in all footers

## Adding a Profile Photo

Replace the placeholder initials block in `index.html` with:

```html
<img src="photo.jpg" alt="Your Name"
     style="width:150px;height:150px;object-fit:cover;border-radius:50%;
            border:2px solid rgba(200,164,74,0.3);">
```

## Custom Domain (Optional)

Add a `CNAME` file containing your domain (e.g. `yourname.com`) to the repo root,
then configure your DNS provider to point to GitHub Pages.

---

*Site built with pure HTML/CSS — no frameworks, no build steps, no dependencies beyond Google Fonts.*
