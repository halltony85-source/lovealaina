# Love, Alaina

Falling-hearts proposal page. Deploy `love/Alaina/index.html` so it is served at
`https://clickflame.com/love/Alaina`.

The page is no-indexed via `<meta name="robots" content="noindex, nofollow, ...">`.
Do **not** also block `/love/` in `robots.txt` — Google must be able to crawl the
page to see the noindex tag. For belt-and-suspenders, add an
`X-Robots-Tag: noindex, nofollow` response header for `/love/*` at the host.
