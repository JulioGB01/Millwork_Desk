# Millwork Desk

> A lightweight, browser-based reference desk for architectural woodwork professionals.

[Open the live site](https://juliogb01.github.io/Millwork_Desk/)

Millwork Desk brings product categories, a searchable terminology dictionary, and an AWS-oriented section guide into one responsive, zero-build interface.

## What it includes

| Area | Purpose |
| --- | --- |
| Products | Browse architectural woodwork product types by section, with concise drafting prompts and image-search links. |
| Dictionary | Search millwork and drafting terms, filter by letter, and review common abbreviations. |
| Standard guide | Navigate a section-by-section orientation to the Architectural Woodwork Standards (AWS). |

## Features

- Fast client-side search and filtering.
- Keyboard-accessible tabs and controls.
- Responsive layout for desktop, tablet, and mobile.
- No framework, build step, or server required.
- Motion preferences and focus states respected.

## Run locally

```bash
git clone https://github.com/JulioGB01/Millwork_Desk.git
cd Millwork_Desk
python -m http.server 8080
```

Open `http://localhost:8080`. Opening `index.html` directly also works for the current project.

## Project layout

```text
.
├── index.html                  # Application shell
├── style.css                   # Design system and responsive styles
├── script.js                   # Content data and UI behavior
├── .github/workflows/static.yml
└── README.md
```

## Deployment

The included workflow deploys the root of `main` to GitHub Pages. In **Settings → Pages**, select **GitHub Actions** as the deployment source.

## Standards and copyright

This is an independent educational reference, not an official publication of AWI, AWMAC, WI, or any standards body. It does not replace the current licensed Architectural Woodwork Standards, project specifications, or professional judgment.

AWS-related material remains subject to its respective owners’ rights. Verify requirements against the current official source before using this tool for a project, and do not submit copyrighted text or images without permission.

## Contributing

Read [`CONTRIBUTING.md`](CONTRIBUTING.md) before proposing changes.