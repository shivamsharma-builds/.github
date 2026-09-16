# Shivam Sharma — GitHub Pages Profile

This repository is designed as a GitHub Pages profile repository named `.github`.

## Important URL structure

Because the repository itself is named `.github`, the published site uses:

`https://shivamsharma-builds.github.io/.github/`

The Week 00 article therefore uses:

`https://shivamsharma-builds.github.io/.github/blogs/dmi-week-00-internet-and-networking-assignment.html`

## Setup

1. Create a public repository named `.github` under `shivamsharma-builds`.
2. Upload the contents of this repository to the root of that repository.
3. Push to `main`.
4. In GitHub: Settings → Pages → Source → GitHub Actions.
5. Wait for the Pages workflow to deploy.

The `baseurl: "/.github"` and `.html` permalink are intentional and are what produce the desired URL structure.
