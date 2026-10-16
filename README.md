# CashCheck — legal & support pages

Public because GitHub Pages only serves public repositories. It contains no
source code — the app itself lives in the private CashCheck repo.

- `privacy.html` — the Privacy Policy URL the App Store listing requires, also
  linked from the app's Settings screen
- `support.html` — the Support URL the App Store listing requires, also linked
  from Settings

Both URLs are compiled into the app (`CashCheck/Model/Links.swift`) and listed
in App Store Connect. **Moving or renaming this repository changes the URLs.**
GitHub redirects repository links after a transfer, but not the Pages address,
so the old URL would 404 while the app still pointed at it. A move needs a new
build and a metadata update shipped together — never mid-review.

| | |
|---|---|
| Privacy policy | https://fenuaora.github.io/cashcheck-legal/privacy.html |
| Support | https://fenuaora.github.io/cashcheck-legal/support.html |
