# Creative portfolio template

An experimental, responsive portfolio built with React, TypeScript, and Vite.
It is configured to deploy to GitHub Pages through the workflow in
`.github/workflows/deploy.yml`.

## Customize

Most content is grouped at the top of `src/App.tsx`:

- Update the `profile` object with your name, bio, email, and social links.
- Replace the entries in `projects` with your actual work.
- Replace the entries in `experience` with your work history.
- Change the initials in the `wordmark` link.
- Adjust colors in `src/index.css`.
- Update the page title and description in `index.html`.

Project links currently use `#`. Replace them with live sites or case-study
URLs. The geometric project art is CSS-based, so it can be kept as-is or
replaced with screenshots inside each `.project-visual`.

## Develop locally

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages

1. Push the repository to GitHub.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push to `main`. The included workflow builds and deploys the site.

The Vite `base` is set to `./`, so the build works for both account sites and
repository sites.
