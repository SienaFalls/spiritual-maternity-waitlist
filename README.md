# Spiritual Maternity — Waitlist Landing Page

Waitlist page for **Spiritual Maternity: The Vocation of Every Woman**, a six-week
live study taught by Genevieve Kineke for House of Gold.

## Files

| File | Purpose |
|---|---|
| `index.html` | The page. Self-contained: no build step, no dependencies. |
| `cover.jpg` | Course cover, 880 × 1100, shown in the hero. |

Open `index.html` in a browser, or serve the folder. Nothing to install.

## Design

Built on the House of Gold design tokens from `house-of-gold/assets/css/theme.css`:
Cormorant Garamond and Jost, gold `#D0AA5A`, Marian blue `#284268`, parchment
surfaces. The page can be lifted into the WordPress theme as a `wp:html` pattern
without restyling.

The cover uses Jana Thork and Kepler Std, matching the Domus Aurea podcast cover.
The artwork is the Visitation from a twelfth-century Aquitaine psalter.

## Signup form

Posts to a Kit form dedicated to this cohort. Double opt-in is off.

The form targets a hidden iframe rather than submitting through `fetch`. This is
deliberate: a background `fetch` is blocked by CORS, including from pages opened
directly from disk. A small script swaps in an inline confirmation afterward, and
with JavaScript disabled the plain form post still works.

## Deploying

Static files. Copy the folder contents to the web root or a subfolder on the
server. No server-side requirements.
