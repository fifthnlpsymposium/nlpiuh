# 5th NLP Symposium — Isra University Hyderabad

Website for the 5th NLP Symposium, organized by the Department of Computer Science, Isra
University Hyderabad, held **Thursday, September 17, 2026**.

Built from [mikepierce/conference-website-template](https://github.com/mikepierce/conference-website-template)
(plain HTML/CSS, GPLv3 — see `LICENSE`).

## Structure

- `index.html` — home page (welcome text, confirmed speakers/panelists, organizing committee)
- `registration/` — Register Now button linking to the Google Form
- `program/` — full-day schedule
- `directions/` — venue map and travel info
- `flyer/` — downloadable flyer (PNG + PDF, color and grayscale; `*-thumb.jpg` are the smaller
  on-page preview images, the `.pdf`/`.png` are full resolution)
- `assets/` — images, banner, favicon, and `main.css` (all site styling/colors)
- `sitemap.xml` — for search engines; update the URLs if you use a custom domain

## Still to fill in

Search each page for `TODO` / `[Add ...]` / "More information coming soon" markers — these mark
placeholder content that still needs real details:

- [x] Banner, favicon and flyer artwork (`assets/banner.jpg`, `assets/favicon.png`,
      `assets/NLPSymposium-Flyer*`) — final branded assets supplied and in place
- [x] Site colors and section headings (`assets/main.css`) — navy/teal/purple/gold palette mixed
      from the banner and flyer artwork; "pill" headings color-coded by section (teal = speakers,
      purple = panel, blue = general info)
- [x] Expert-talk speaker names (`program/index.html`, homepage) — Prof. Dr. Muhammad Rafi, Raza
      Abbas, Dr. Wazir Ali, Mr. Adnan Zaidi confirmed; fifth slot listed as "Industry Expert"
      pending a name
- [x] Panel discussion panelists (`program/index.html`, homepage) — all 5 confirmed
- [x] Google Form link for registration (`registration/index.html`) —
      https://forms.gle/rbLUJRbvEQNWyk7A9
- [x] Venue (`directions/index.html`) — Asadullah Kazi Auditorium, Isra University, Hyderabad
- [x] Contact email — `fifthnlpsymposium@gmail.com` (registration page)
- [ ] Talk titles and abstracts for each expert talk (currently "More information coming soon")
- [ ] The fifth expert talk speaker's name, once confirmed
- [ ] Panel discussion topic and moderator (currently "More Information Coming Soon")
- [ ] Organizing committee members (homepage currently says "More information coming soon")
- [ ] Accommodation recommendations (`directions/index.html`)
- [ ] Sponsor logos, if any (commented out in `index.html` until confirmed)

## Publishing with GitHub Pages

1. In this repo, go to **Settings → Pages**.
2. Under **Source**, choose the `main` (or `master`) branch, root folder.
3. Save — the site will publish at `https://fifthnlpsymposium.github.io/nlpiuh` (or your custom
   domain, if you set one up under **Settings → Pages → Custom domain**).
4. Update `sitemap.xml` if your final URL differs from the default above.

## Local preview

No build step is required — it's static HTML/CSS. To preview locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.
