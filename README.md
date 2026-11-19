# Atharv Gupta — Portfolio

Source for my personal portfolio site.

**Live:** https://atharvguitarist.github.io/Portfolio-Website

## About

I'm an AI engineer based in Delhi NCR. I train the models, wire up the agents, and build the product around them. Engineer at IBM, independent consultant with 50+ deliveries, studying for an M.Tech in AI/ML at BITS Pilani.

The site covers my AI work with measured results, my certifications, SmartPanel (a 7-inch ESP32-S3 home control panel I designed and wrote ~6,900 lines of firmware for), selected projects, and experience.

## Technical notes

The whole site is a single self-contained `index.html` — no build step, no dependencies, no framework. Fonts load from Google Fonts; everything else, including the illustrations and the cursor-tracking cat, is inline SVG, CSS and vanilla JavaScript.

| Item | Detail |
| --- | --- |
| Type | Bricolage Grotesque, IBM Plex Sans, IBM Plex Mono |
| Size | ~60 KB, single file |
| Hosting | GitHub Pages |
| Accessibility | Keyboard focus states, reduced-motion support, responsive to mobile |

### Keeping it current

Near the top of the script block there's a `PROFILE` object holding every number on the page — projects delivered, firmware lines, accuracy figures, and the certificate list. Edit those values and the page follows. Years of experience and role durations compute themselves from start dates, so they never go stale.

To link a certificate, upload the PDF to a repo, open it, press **Raw**, and paste that URL into the matching `pdf` field in `PROFILE.certificates`.

## Contact

Email: atharvg06@gmail.com
GitHub: https://github.com/atharvguitarist
LinkedIn: https://linkedin.com/in/atharvguitarist





















