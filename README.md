# Uttaravalli Uma – Personal Portfolio

A responsive, white-themed portfolio and printable resume for Uttaravalli Uma. It is built with HTML5, CSS3, and Bootstrap 5 as a static site, with no build step or backend.

## Features

- Responsive single-page portfolio
- Career objective, education, skills, internships, project, certifications, and achievements
- Clickable phone, email, LinkedIn, and GitHub contact links
- Separate resume page with a print-to-PDF option
- Netlify configuration included

## Project Structure

```text
├── index.html
├── resume.html
├── netlify.toml
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       └── uma.jpg.jpeg
└── README.md
```

## Run locally

Open `index.html` directly in a browser, or serve this directory with any static file server. No package installation or build command is required.

## Deploy to Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project** and connect the GitHub repository.
3. Leave the build command empty and set the publish directory to `.`. These settings are also in [`netlify.toml`](./netlify.toml).
4. Deploy the site. Netlify will publish updates when the configured Git branch receives new commits.

The site is static; do not configure a server-side build command.
