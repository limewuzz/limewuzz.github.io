# limewuzz's Academic Homepage

[![pages-build-deployment](https://github.com/limewuzz/limewuzz.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/limewuzz/limewuzz.github.io/actions/workflows/pages/pages-build-deployment)

This is the source code for my academic personal homepage, built with [academicpages](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub Pages.

🔗 **Live Site**: [https://limewuzz.github.io](https://limewuzz.github.io)

## About

Update `_config.yml` and the files under `_pages/`, `_projects/`, and `_publications/` with your own information.

## Quick Start

### 1. Fork & Rename
1. Fork [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)
2. Rename to `limewuzz.github.io`

### 2. Upload These Files
Copy all files from this archive to your repository:
```
limewuzz.github.io/
├── _config.yml              # Site configuration
├── _data/
│   └── navigation.yml        # Navigation menu
├── _pages/
│   ├── about.md              # Homepage
│   ├── publications.md       # Publications list
│   ├── projects.md           # Projects list
│   └── cv.md                 # CV page
├── _publications/
│   └── 2025-05-01-synthetic-data-robust-reading.md
├── _projects/
│   ├── 2025-09-01-vlm-decision-control.md
│   ├── 2025-06-01-metro-qa.md
│   └── 2025-08-01-generative-recommender.md
├── images/
│   └── profile.png           # Your photo (upload yourself)
└── files/
    └── cv.pdf                # Your CV PDF (upload yourself)
```

### 3. Enable GitHub Pages
- Go to **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **master** or **main** → `/ (root)`
- Click **Save**

### 4. Add Your Photo
- Upload your profile photo to `images/profile.png`
- Recommended size: 500x500px, square format

### 5. Add Your CV PDF
- Upload your CV PDF to `files/cv.pdf`
- Update the download link in `_pages/cv.md` if needed

## Customization Guide

### Update Personal Info
Edit `_config.yml`:
```yaml
name: "limewuzz"
email: "your-email@example.com"
github: "limewuzz"
```

### Add New Publication
Create a new file in `_publications/` with format:
```
YYYY-MM-DD-paper-title.md
```

### Add New Project
Create a new file in `_projects/` with format:
```
YYYY-MM-DD-project-name.md
```

### Update Navigation
Edit `_data/navigation.yml` to add/remove menu items.

## Technology Stack

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [academicpages](https://github.com/academicpages/academicpages.github.io) - Academic theme
- [GitHub Pages](https://pages.github.com/) - Hosting

## License

The academicpages theme is open source under [MIT License](https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE).

Content (text, images) is yours.
