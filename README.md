# NAT X — Website

Marketing site for **NAT X Co., Ltd.** — the software and innovation arm of NAT Group
(a wholly-owned subsidiary of NAT Absolute Technologies Public Company Limited, MAI: NAT).

Static single-page site built with plain HTML and CSS.

## Structure

```
.
├── index.html        # single-page site
├── styles.css
├── .nojekyll         # opt out of Jekyll on GitHub Pages
└── .github/workflows/pages.yml   # auto-deploys to GitHub Pages on push
```

## Local preview

Any static server works:

```sh
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deployment

Pushing to `claude/design-nat-x-website-mopW6` or `main` triggers the Pages
workflow. Enable Pages once in the repo settings (Settings → Pages → Build and
deployment → Source: **GitHub Actions**).

## Content notes

Follows the editorial rules in `nat-group-website-content.md`:

- British spelling, active voice, present tense.
- Outcome before feature.
- Capability-level language only for SaMD work. Specific programmes, partners,
  and clinical registrations are withheld pending TFDA milestone.
- Attribution is mandatory — this site represents **NAT X** within the broader
  NAT Group (NAT Absolute · NAT X · NAT Venture).
