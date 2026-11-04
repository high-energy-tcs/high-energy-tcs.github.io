# High-Energy TCS

A responsive, static research-group website for High-Energy TCS at Bocconi University. All 12 members and the supplied email addresses are included.

## Preview

No dependencies or build tools are required. Open `index.html` directly, or run:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## GitHub Pages

In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. After committing and pushing the files, GitHub Pages will serve the site at <https://high-energy-tcs.github.io/>. The `.nojekyll` file enables static hosting with no theme or build step.

## Editing

- `index.html`: content, member cards, roles, research interests, profile links and email addresses. Members follow the supplied order.
- `assets/style.css`: colors, typography, layout and responsive styles.
- `assets/people/`: local portraits. Replace a placeholder with an `<img>` inside the person's `.portrait` link, following the existing cards. Adjust `object-position` if needed.
- `assets/people/sources.json`: portrait provenance, including source pages and image URLs.

The page works without JavaScript, external fonts or third-party runtime requests. It includes keyboard focus styles, a skip link and reduced-motion support.

## Sources

Roles and research summaries were checked against Bocconi faculty profiles, its [theory group directory](https://cs.unibocconi.eu/research/theory), and personal sites linked from that directory on 4 November 2026. Cards link to the relevant profiles. Names and email addresses follow the supplied list, including Jonas's `@phd.unibocconi.it` address; Laura's supplied `AT` is normalized to `@`.

Seven portraits come from Bocconi faculty profiles. Mariana Gama's and Paul Lou's portraits come from their personal sites linked by Bocconi. Images remain attributable to their original owners; no image license is asserted by this repository.

Jeffrey Champion and Jonas Schmidt have initials placeholders because their Bocconi profiles show default icons. Valerio Cini's personal-site image could not be downloaded (HTTP 403), so he also has an initials placeholder. Replace these with supplied portraits later. The attempted image URL is recorded in `sources.json`.
