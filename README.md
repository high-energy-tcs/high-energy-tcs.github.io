# High-Energy TCS

Open `index.html` in a browser to preview the site. To update the existing GitHub Pages repository, copy the contents of this folder into the repository root and merge the `assets/` folder. The existing Pages configuration serves these files directly.

## Edit the objective and lists

To add the objective, insert a paragraph below the Objective heading in `index.html`.

The three lists live in `index.html`. Add one `<li>` per organizer, participant or solved problem. Each entry can be plain text or a link. The empty-list message disappears when you add the first entry.

For a person with a profile, use this form and substitute their name and profile URL.

```html
<li><a href="PROFILE_URL">Name</a></li>
```

For a solved problem, link the title to its paper or write-up.

```html
<li><a href="SOLUTION_URL">Problem title</a></li>
```

## Design files

- `assets/logo.svg` is the editable vector logo.
- `assets/favicon.svg` is the small-size version for browser tabs.
- `assets/style.css` sets the typography, colors, spacing and responsive layout.
