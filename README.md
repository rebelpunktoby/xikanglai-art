# xikanglai.art

Website of sculptor Xikang Lai 賴錫康. Static HTML, no build step, no dependencies.

- `public/`: the website, deployed by Cloudflare Pages (build command: none; output directory: `public`).
  - `index.html`: the exhibition (four chapters, 27 works, About, Contact).
  - `in-the-round.html`: In the Round 雕塑・環視, reserved for future 3D viewing.
  - `assets/img/`: 1600 px images, `assets/img/thumb/`: 800 px.
  - `_headers`: cache and security headers for Cloudflare Pages.
- `docs/manifest.json`, `docs/manifest.csv`: every work with its sources and verification notes (not deployed).

Every push to `main` deploys automatically. Release `v1.0.0` is the first production version.
Source archives (catalogue PDF, archive zip) are kept off the repository.
