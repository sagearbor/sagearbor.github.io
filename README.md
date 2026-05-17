# sagearbor.github.io

User site for [@sagearbor](https://github.com/sagearbor) — serves at
**https://sagearbor.github.io/**.

## Layout

```
/                       → landing page (this repo's index.html)
/fitrival/              → FitRival app website + privacy policy
/fitrival/privacy.html  → the Play Store / App Store privacy policy URL
```

To add a future app's site, just create a new folder at the repo root
(e.g. `/myapp/`) with its own `index.html` + `privacy.html`. No build
step — push and GitHub Pages serves it directly.

## Enabling Pages (one-time)

`Settings → Pages → Source: Deploy from branch → main / (root) → Save`.
Site goes live within ~1 min.
