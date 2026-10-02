# Noble Ball — former GitHub Pages mirror

This repository only redirects to the live site, **https://noble-ball.com** (source: the private
`class-chauffeur` repository, deployed to Cloudflare).

`index.html` and `404.html` send every visitor there (0-second meta refresh + script), carry
`rel="canonical"` pointing at the live site and `noindex`, so search engines never index this copy.
GitHub Pages cannot issue HTTP 301 redirects, which is why the pages do it themselves.

The old standalone page and its images are in the git history (commit `bcd39f6`).
