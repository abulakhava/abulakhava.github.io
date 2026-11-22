# abulakhava.github.io

Privacy policies and support pages for abulakhava mobile apps, served by GitHub
Pages at <https://abulakhava.github.io/>.

One folder per app; these URLs go into App Store Connect / Google Play, so never
move or rename a published page:

| App | Privacy Policy URL | Support URL |
|---|---|---|
| Winter Corner: Cozy Advent | `/winter-corner/privacy/` | `/winter-corner/support/` |

- Plain static HTML, no build step (`.nojekyll` disables Jekyll).
- Shared style in `assets/style.css` (app palette, blurred room backdrop, string
  of lights, CSS snow that stops under reduced motion). The Comfortaa font
  (`assets/fonts`, SIL OFL) and the art (`assets/img`, from the app) are
  self-hosted, so the pages make no third-party requests.
- A policy's source of truth lives in the app's repo (Winter Corner:
  `docs/PRIVACY.md`, also shown in the app). Update both together.
