# Security portfolio

One page presenting four projects from the same home lab.

**Tools I built**

- **[websec-audit](https://github.com/biggjayy2000/websec-audit)** — a web security scanner with an
  authorization guard and severity-ranked reports.
- **[logtriage](https://github.com/biggjayy2000/logtriage)** — detection over SSH auth and web access
  logs, with eight MITRE-mapped rules and incident reports.

**Engagements**

- **[juice-shop-pentest](https://github.com/biggjayy2000/juice-shop-pentest)** — a penetration test with
  four confirmed findings, a client-ready report, and 20 screenshots of evidence.
- **[ad-home-lab](https://github.com/biggjayy2000/ad-home-lab)** — building and enumerating an Active
  Directory domain controller, from anonymous LDAP to SYSVOL and Kerberos, across 29 screenshots.

Plus six lab writeups linked from the page and held in
**[labs](https://github.com/biggjayy2000/labs)**: Active Directory reconnaissance, an internal
security audit, NIST CSF incident analysis, SQL log investigation, Linux permissions, and password
hash auditing.

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

Every screenshot on the page comes from a real run — the tools' terminal output, the Juice Shop request
captured in Burp, and the lab's nmap output. No mock-ups.
