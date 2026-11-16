# Zero Byte — Drone Project

A single-page animated showcase of Team Zero Byte's drone project and the people who built it.

## Features

- 3D drone (three.js) that flies between sections as you scroll
- Pinned 360° view that rotates the drone with scroll
- Scroll reveals, count-up stats, scroll-driven text band, landing sequence
- Responsive, and respects `prefers-reduced-motion`

## Run it

It is one static file with no build step. Serve the folder (the page loads `content.json`, so opening the file directly will not work):

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. An internet connection is needed: three.js and the font load from a CDN.

## Edit the content

All text, stats, features and team members live in `content.json`. Edit them from the admin page:

**https://ishfaqbuilds.github.io/zerobyte/admin/**

1. Create a fine-grained GitHub token (GitHub → Settings → Developer settings → Fine-grained tokens) limited to this repository with **Contents: Read and write**.
2. Paste it into the admin page, make your changes, upload photos, and press **Save changes**.
3. The live site updates in about a minute.

Anyone can open the admin page, but only someone with write access to this repository and their own token can save. The token stays in the browser tab and is sent only to GitHub.

The stats, features and 360° part labels are currently placeholders and should be replaced with the drone's real specs.

## Team

- Mohammad Ishfaqul Islam
- MD. Arifur Rahman
- Sayeed Omar
- Sayeed Abrar Aqil
- Thasinur Mohian
- Alim Shahriar
- MD. Minhaz Uddin
