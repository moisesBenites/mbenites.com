# mbenites.com

Personal site, served by GitHub Pages at <https://mbenites.com>.

## Layout

| Path | Serves |
| --- | --- |
| `index.html` | Home / portfolio |
| `style.css` | Single stylesheet for every page |
| `favicon.svg` | Site favicon (MB monogram) |
| `rudder/` | Support page for the Rudder Safari extension |
| `rudder/privacy/` | Privacy policy for Rudder |
| `CNAME` | Custom domain claim for `mbenites.com` |
| `.nojekyll` | Serve files as-is, skip Jekyll |

`rudder/icon.svg` is a copy of `design/icon.svg` from the Rudder repository.
Re-copy it if the app icon changes.

Every path is relative, so the site also works unchanged at
`https://moisesbenites.github.io` before DNS is pointed.

## App Store Connect

These two URLs are referenced by the Rudder App Store listing and must stay
reachable:

- Support URL: <https://mbenites.com/rudder/>
- Privacy Policy URL: <https://mbenites.com/rudder/privacy/>

## Adding a product

Create a folder named after it, with its own `index.html` and `privacy/`,
linking `../style.css`. Then add a card to the project list in `index.html`.
