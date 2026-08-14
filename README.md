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

`index.html` is the single source of truth. Edit it and push. GitHub Pages
redeploys in about a minute and **the URL does not change**, so any QR code
already printed keeps working.

Keep the two `<meta>` tags in `<head>` intact, particularly:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

Without it, phones lay the page out at roughly 980px and scale the whole thing
down, so the responsive card layout never activates and the schedule is
unreadable on exactly the device people use to scan the QR code. Check any
change on a phone, not just a desktop browser window narrowed with the mouse —
a narrow window still triggers the mobile layout and hides this class of bug.

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
