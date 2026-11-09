# Selorm Kalitsi — Personal Portfolio

**Live website:** https://slrm1.github.io/work/

A single-page, responsive portfolio for software engineering, applied AI/NLP, research, UX and HCI, game development, and systems programming. Updated November 2026.

## What's inside

- Existing featured UX case studies and a self-contained portrait.
- **33 documented projects** in an interactive archive with text search, category filters, and accessible project-detail dialogs.
- Featured work: AfroLearn, The Yard Studio, NFL Big Data Bowl research, Career Launchpad, WasteLess/HerdWise, and the Unofficial Howard CS Guide.
- Academic, hackathon and research projects clearly distinguished from launched products.
- Experience in software development, NLP research and community outreach.
- Skills, hackathon honors, GitHub/LinkedIn/email links.

## Publishing

This repository is public and GitHub Pages is configured to publish from the **main branch, root folder**. No package manager or deploy build is required.

The page is self-contained in `index.html`; CSS and JavaScript are inline, and the profile photo is embedded. It should also work when `index.html` is opened locally.

## Updating content

- Main layout, colors and typography: edit the CSS inside `index.html`.
- Project list: look for `const portfolioProjects =` near the end of `index.html`. Each entry has a title, category, status, year, description, stack, role, and optional links.
- Filters: text search combines with category selection, and selecting a new category clears the previous search query.
- Experience and awards: edit the `#experience` section.

## Representation and privacy

Descriptions are intentionally careful about project maturity: research is research, mockups are mockups, coursework is labeled, and private repositories are not linked to the public. Some public links belong to demos or third-party dashboards and may depend on their hosting providers.

This is an individual portfolio, not an official Howard University website.
