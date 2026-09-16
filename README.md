# Shivam Sharma — GitHub Pages Profile

This repository is intended to be named **`.github`** under `shivamsharma-builds`.

## Exact blog URL

After GitHub Pages deployment, Week 00 is:

`https://shivamsharma-builds.github.io/.github/blogs/dmi-week-00-internet-and-networking-assignment.html`

## Deployment

1. Create a **public** repository named `.github`.
2. Upload the contents of this repository to the **root** of that repository.
3. Push to `main`.
4. Open **Settings → Pages**.
5. Set **Source** to **GitHub Actions**.
6. Wait for the `Deploy GitHub Pages` workflow to finish.

The important settings are:

- `baseurl: "/.github"`
- `permalink: /blogs/:title.html`

These are intentional because `.github` is the repository name and the desired public URL contains `/.github/`.

## Internship repository

https://github.com/shivamsharma-builds/devops-micro-internship-pravinmishra
