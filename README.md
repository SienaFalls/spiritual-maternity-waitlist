# Under Mary's Mantle — Course Landing Page

Landing page for **Under Mary's Mantle: The Feminine Soul**, a six-week live
study taught by Genevieve Kineke for House of Gold. Thursdays, September 24
through October 29, 2026, at 7:30 pm Eastern. Twenty-five seats, $59.

The folder is still named `spiritual-maternity-waitlist` and the page is still
served from that path. Renaming it would break every tracking link already
circulating, so the name stays even though the page is no longer a waitlist.

## Files

| File | Purpose |
|---|---|
| `index.html` | The page. Self-contained: no build step, no dependencies. |
| `cover.jpg` | Course cover, 1080 × 1350, shown in the hero and used as the OG image. |
| `privacy.html` | Privacy notice, linked from the footer. |
| `TRACKING-LINKS.md` | UTM-tagged links for each placement, and how to read them in Analytics. |

Open `index.html` in a browser, or serve the folder. Nothing to install.

## Design

Built on the House of Gold design tokens from `house-of-gold/assets/css/theme.css`:
Cormorant Garamond and Jost, gold `#D0AA5A`, Marian blue `#284268`, parchment
surfaces. The page can be lifted into the WordPress theme as a `wp:html` pattern
without restyling.

The cover uses Jana Thork and Kepler Std, matching the Domus Aurea podcast cover.
The artwork is the Visitation from a twelfth-century Aquitaine psalter.

## Registration

Registration and payment happen entirely on the Kit product page:

```
https://my-secret-is-mine.kit.com/products/under-the-mantle-of-mary-the-feminine-
```

The page collects nothing itself. There is no form, no Kit script, and no
third-party JavaScript of any kind. All three calls to action, the header
button, the hero button, and the register band at the foot of the page, point
at that one URL. If the course price, the dates, or the product URL change,
those three links and the register band copy are the only places to edit.

Two names are in play: this page says *Under Mary's Mantle: The Feminine Soul*
and the Kit product says *Under the Mantle of Mary: The Feminine Soul*. They
should be reconciled in Kit.

Through August 12, 2026, the page was a waitlist with an embedded Kit form,
uid `62ddea07c5`. That form still exists in Kit and holds the pre-launch list.
It is no longer referenced here. If a future cohort needs a waitlist again, the
embed and its styling are recoverable from the git history, commit `b7bff94`
and earlier.

## Deploying

Static files. Copy the folder contents to the web root or a subfolder on the
server. No server-side requirements.
