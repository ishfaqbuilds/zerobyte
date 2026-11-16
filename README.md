# Zero Byte — Drone Project

A single-page animated showcase of Team Zero Byte's drone project and the people who built it.

## Features

- 3D drone (three.js) that flies between sections as you scroll
- Pinned 360° view that rotates the drone with scroll
- Scroll reveals, count-up stats, scroll-driven text band, landing sequence
- Responsive, and respects `prefers-reduced-motion`

## Run it

It is one static file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. An internet connection is needed: three.js and the font load from a CDN.

## Edit the content

Everything is in `index.html`:

- **Team and features** — the `team` and `features` lists at the top of the first `<script>`. Add `role: "..."` or `img: "photo.jpg"` to a team member.
- **Stats** — the `data-count` values in the `.stats` block.
- **360° part labels** — the `.callout` blocks in the `#explore` section.

The stats, features and part labels are currently placeholders and should be replaced with the drone's real specs.

## Team

- Mohammad Ishfaqul Islam
- MD. Arifur Rahman
- Sayeed Omar
- Sayeed Abrar Aqil
- Thasinur Mohian
- Alim Shahriar
- MD. Minhaz Uddin
