# net-redirect
redirects to safetravelsmobilerepair.com

Sends every address on **SafeTravelsMobileRepair.net** to the same page on **SafeTravelsMobileRepair.com**
(e.g. `safetravelsmobilerepair.net/services/` → `safetravelsmobilerepair.com/services/`).

- `index.html` and `404.html` are the same redirect page: GitHub Pages serves `404.html` for any path that
  doesn't exist, so every path redirects. The script keeps the path, query and `#anchor`; the meta refresh
  is a fallback to the home page when JavaScript is off.
- `CNAME` sets the GitHub Pages custom domain to `safetravelsmobilerepair.net`.
- Nothing private belongs in this repo.
