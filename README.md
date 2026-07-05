# WearMe AI — Website

Static marketing + compliance website for **WearMe AI**, ready to deploy on
GitHub Pages.

## Pages

| Path                | File                          | Purpose                                   |
| ------------------- | ----------------------------- | ----------------------------------------- |
| `/`                 | `index.html`                  | Home / landing page                       |
| `/privacy-policy`   | `privacy-policy/index.html`   | Privacy Policy (Google Play requirement)  |
| `/delete-account`   | `delete-account/index.html`   | Account & data deletion (Play requirement)|

The pages use folder-based `index.html` files so the URLs resolve cleanly as
`/privacy-policy/` and `/delete-account/` without `.html` extensions.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select your branch and set the folder to **`/website`** (or move the contents
   of `website/` to the repo root / a `docs/` folder and point Pages there).
5. Save. Your site publishes at `https://<user>.github.io/<repo>/`.

A `.nojekyll` file is included so GitHub Pages serves all files as-is (no Jekyll
processing).

## Design

Dark-premium fashion-tech aesthetic that matches the app: obsidian canvas,
violet → magenta brand gradient, glassmorphism cards and the Inter typeface.
All styling lives in `assets/style.css`; the brand mark is `assets/logo.png`.

## Support / contact

All support and account-deletion links point to
**harshadsalunke2002@gmail.com**.
