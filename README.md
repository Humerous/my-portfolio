# David Miller Portfolio

Personal portfolio website for David Miller, a Cape Town-based full-stack developer and creative technologist.

## Live Site

Current Git-backed production:

https://my-portfolio-david-millers-projects-2889e321.vercel.app/

Legacy alias still serving the older portfolio:

https://my-portfolio-three-black.vercel.app/

## Current Version

This repository contains the current portfolio design restored from the verified Vercel deployment `HXxT4LB51HTCA5AgcUD439b2J4ZF`.

The site includes:

- Selected work
- About
- Capabilities
- Contact
- Responsive desktop and mobile layouts
- Accessible navigation and interactions

## Technology

- HTML5
- CSS3
- Vanilla JavaScript

There is no package manager, framework dependency, database, or build step required for local development.

## Project Structure

```text
my-portfolio/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── script.js
    └── img/
        └── website and project images
```

## Run Locally

From the project folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Stop the server with `Control + C`.

## Development Workflow

```text
LOCAL PROJECT
→ TEST LOCALLY
→ GIT COMMIT
→ GITHUB main
→ VERCEL
→ PRODUCTION
```

Before pushing changes:

```bash
git status
git diff
```

Commit and push approved changes:

```bash
git add .
git commit -m "Describe the change"
git push origin main
```

Vercel is connected to this repository and deploys updates from the production branch.

## Recovery Record

The current design was recovered from verified Vercel deployment:

`HXxT4LB51HTCA5AgcUD439b2J4ZF`

The recovered deployment source consisted of:

- `index.html`
- `assets/css/styles.css`
- `assets/js/script.js`

Existing repository image assets were retained because the current portfolio references them.

A safety branch preserves the repository state from before recovery:

`backup-pre-HXxT4-recovery-2026-08-09`

## Repository

https://github.com/Humerous/my-portfolio

## Author

David Miller  
Cape Town, South Africa

## License

MIT
