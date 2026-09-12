# dom

Static single-page tool at https://dom.cptjanst.se

Drop a `.docx`, `.doc`, `.txt` or `.md` file. Everything runs client-side:

- whole-word `de` / `dem` → `dom` (case-preserving: `De`→`Dom`, `DEM`→`DOM`)
- all paragraph breaks removed, except the one after the phrase »nu kör vi»
- result offered as `<name>-dom.txt` download + copy button

`.docx` is read with [mammoth.js](https://github.com/mwilliamson/mammoth.js) (CDN). Legacy binary `.doc` uses a best-effort heuristic.

Hosted on GitHub Pages; DNS is a CNAME in the `cptjanst.se` Cloudflare zone → `inthevidual.github.io`.
