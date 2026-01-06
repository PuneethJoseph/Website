# Puneeth Joseph - Personal Portfolio Website

Personal portfolio website for **puneethjoseph.in** - A bilingual (English/Deutsch) professional website showcasing software engineering experience, skills, and projects.

## 🎯 Purpose

This repository contains the source code for the personal portfolio website hosted at **puneethjoseph.in**. The website serves as:

- **Professional Portfolio** - Showcase of 14+ years of experience in automotive software engineering
- **Resume Hosting** - Downloadable resume PDFs in English and German
- **Contact Hub** - Professional contact information and links
- **Project Showcase** - Highlighting key projects including MB.OS development and ConTra application

## 📁 Repository Structure

```
/
├── index.html                    # Main webpage (bilingual)
├── config.js                     # Configuration (URLs, file paths)
├── robots.txt                     # SEO - Search engine crawler instructions
├── sitemap.xml                    # SEO - XML sitemap
├── README.md                      # This file
├── VERSION                        # Version number
│
├── assets/
│   └── images/
│       └── logo-favicon.svg      # Favicon
│
├── pdfs/
│   ├── Puneeth_Joseph_Resume.pdf           # English resume PDF
│   └── Puneeth_Joseph_Lebenslauf.pdf       # German resume PDF
│
└── resume/
    ├── resume-pdf.html           # Source for English resume PDF
    └── resume-pdf-de.html       # Source for German resume PDF
```

## 🔧 Configuration

All configurable URLs and paths are in `config.js`:

- **ConTra Application URL** - `contraUrl`
- **Resume PDF Paths** - `resumePdfUrlEn`, `resumePdfUrlDe`

Update these without modifying `index.html`.

## 📝 Content Management

- **Bilingual Content** - All translations are in `index.html` JavaScript `translations` object
- **Resume Updates** - Edit `resume/resume-pdf.html` (English) or `resume/resume-pdf-de.html` (German), then generate PDFs
- **Main Content** - All website content is in `index.html`

## 🌐 Languages Supported

- **English (EN)** - Default language
- **Deutsch (DE)** - Full German translation

Language preference is saved in browser localStorage and auto-detected from browser settings.

## 📄 Resume Files

- **English**: `pdfs/Puneeth_Joseph_Resume.pdf`
- **German**: `pdfs/Puneeth_Joseph_Lebenslauf.pdf`

To regenerate PDFs:
1. Open `resume/resume-pdf.html` or `resume/resume-pdf-de.html` in browser
2. Print to PDF (Ctrl+P / Cmd+P)
3. Save as the corresponding PDF filename in `pdfs/` folder

## 🔒 Privacy & Security

- No tracking scripts (Google Analytics commented out)
- No external form services (direct email link)
- All content is static HTML/CSS/JavaScript
- No server-side processing required

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- **Lighthouse Score**: 95+ (expected)
- **Load Time**: < 2 seconds
- **Dependencies**: Font Awesome CDN only
- **File Size**: Optimized for fast loading

## 📧 Contact

- **Email**: puneeth.joseph@yahoo.com
- **LinkedIn**: [linkedin.com/in/puneethjoseph](https://www.linkedin.com/in/puneethjoseph)
- **GitHub**: [github.com/puneethjoseph](https://github.com/puneethjoseph)

## 📜 License

Personal use - All rights reserved

---

**Version**: See `VERSION` file  
**Last Updated**: January 2025
