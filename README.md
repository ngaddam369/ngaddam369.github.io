# Nihar Gaddam — Portfolio

Source for my personal portfolio site.

**Live:** https://ngaddam369.github.io

A single-page site covering my work as a Software Development Engineer — distributed systems, Kubernetes, and cloud infrastructure in Go. Built to be fast, accessible, and easy for recruiters to scan while still showing the engineering depth underneath.

## Stack

Intentionally dependency-free: one hand-written `index.html` with inline CSS and vanilla JavaScript. No framework, no build step, no bundler.

- Static HTML/CSS/JS — loads instantly and scores high on Core Web Vitals
- A typed-terminal hero, scroll-triggered reveals, animated counters, and a recruiter/developer toggle, all in ~12 KB of JS
- Fully responsive (mobile → ultra-wide) and `prefers-reduced-motion` aware
- ATS-friendly: all text is selectable, no images of text

## Run locally

No tooling required. Open `index.html` directly, or serve it so the contact form and résumé link behave like production:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

> Note: the Formspree contact form only submits from a real domain, not from a `file://` path — test it on the deployed site.

## Structure

```
.
├── index.html                  # the entire site
├── Nihar_Gaddam_Resume_26.pdf  # linked by the "Download résumé" button
└── README.md
```

## Featured projects

The systems showcased on the site, each with its own docs and benchmarks:

- [timberdb](https://github.com/ngaddam369/timberdb) — time-partitioned, TTL-native LSM storage engine ([docs](https://ngaddam369.github.io/timberdb/))
- [svid-exchange](https://github.com/ngaddam369/svid-exchange) — Zero Trust SPIFFE-to-JWT token exchange service ([docs](https://ngaddam369.github.io/svid-exchange/))
- [saga-conductor](https://github.com/ngaddam369/saga-conductor) — saga orchestrator for distributed transactions ([docs](https://ngaddam369.github.io/saga-conductor/))

## Contact

- Email: nihar.ignis@gmail.com
- LinkedIn: https://www.linkedin.com/in/nihar-gaddam/
- GitHub: https://github.com/ngaddam369
