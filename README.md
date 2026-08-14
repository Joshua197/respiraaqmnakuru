# Nakuru Air Quality Sense-Making Workshop — participant schedule

The participant-facing schedule for the RESPIRA sense-making workshop at Egerton
University, 24–27 August 2026. Published with GitHub Pages so participants can
open it from a QR code without signing in to anything.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The whole site. Self-contained — all styling and all ten partner logos are embedded, so there are no external requests and nothing else has to be uploaded. |
| `logos-source/` | The ten partner logos as individual PNGs, extracted from the partner logo strip. Kept for reuse in banners, programmes and slides. Not needed by the site itself. |

## Updating the schedule

Edit `index.html` and push. GitHub Pages redeploys in about a minute and **the
URL does not change**, so any QR code already printed keeps working.

```bash
git add index.html
git commit -m "Update schedule"
git push
```

## The QR code

The printed QR code encodes the Pages URL for this repository. If the repository
is ever renamed, moved to a different account, or switched to a custom domain,
the URL changes and **every printed QR code stops working** — regenerate and
reprint in that case. Renaming is the easy mistake to make here.

Always print the URL in readable text underneath the QR code, so anyone whose
camera fails can still type it in.
