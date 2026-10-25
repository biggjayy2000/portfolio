# Security portfolio

One page presenting two Python security tools built in the same home lab:

- **[websec-audit](https://github.com/biggjayy2000/websec-audit)** — a web security scanner with an
  authorization guard and severity-ranked reports.
- **[logtriage](https://github.com/biggjayy2000/logtriage)** — detection over SSH auth and web access
  logs, with eight MITRE-mapped rules and incident reports.

Open `index.html` in a browser — the page is self-contained (no CDN, no external fonts), so it works
from a `file://` path or any static host.

## Live

**<https://biggjayy2000.github.io/portfolio/>** — GitHub Pages, `main` / `/ (root)`, HTTPS enforced.
Pushes to `main` rebuild it automatically.

## Contents

```
index.html          the page
images/             screenshots rendered from real tool output
home-page.png       a full-page capture, for quick sharing
```

Screenshots are rendered from actual runs of both tools — not mock-ups.
