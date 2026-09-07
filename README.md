# 5th NLP Symposium — Isra University Hyderabad

Website for the 5th NLP Symposium, organized by the Center for Applied Intelligence and Future
Systems (CAIFS) at Isra University Hyderabad, held **Thursday, September 17, 2026**.

Built from [mikepierce/conference-website-template](https://github.com/mikepierce/conference-website-template)
(plain HTML/CSS, GPLv3 — see `LICENSE`).

## Structure

- `index.html` — home page (welcome text, organizers)
- `registration/` — how to register (Google Form embed goes here)
- `program/` — full-day schedule
- `directions/` — venue map and travel info
- `flyer/` — downloadable flyer (PNG + PDF, color and grayscale)
- `assets/` — images, banner, favicon, and `main.css` (all site styling/colors)
- `sitemap.xml` — for search engines; update the URLs if you use a custom domain

## Still to fill in

Search each page for `TODO` / `[TBA]` / `[Add ...]` markers — these mark placeholder content
that still needs real details:

- [x] Banner image (`assets/banner.jpg`) — final branded banner supplied and in place
- [x] Site colors (`assets/main.css`) — green/gold palette, matched to the banner artwork
- [x] Expert-talk speaker names (`program/index.html`, homepage) — Prof. Dr. Muhammad Rafi, Raza
      Abbas, Dr. Wazir Ali, Mr. Adnan Zaidi confirmed; one industry speaker still TBA (tentatively
      confirmed by Dr. Rafi)
- [x] Panel discussion panelists (`program/index.html`, homepage) — all 5 confirmed
- [ ] Talk titles and abstracts for each expert talk (currently `[Title TBA]` / `[Add talk
      abstract here.]`)
- [ ] The fifth expert talk speaker's name, once confirmed
- [ ] Panel discussion topic and moderator (currently `[Topic TBA]`)
- [ ] Google Form link for registration (`registration/index.html`)
- [ ] Exact venue building/hall and accommodation recommendations (`directions/index.html`)
- [ ] Final flyer artwork (`assets/NLPSymposium-Flyer*.png/.pdf` are still placeholders — update
      with speaker names once talk titles are set, or replace with real designed artwork)
- [ ] Organizing-committee contact email (currently a placeholder: `caifs@isra.edu.pk`)
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
