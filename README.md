# cerkya-remote-legal

Static legal and support pages for the iPhone app **Cerkya: Control Remoto TV** / **Cerkya: Smart TV Remote** (home-screen name: Cerkya Remote), operated by CERKYA S.A.S. (Colombia).

Plain HTML plus one shared stylesheet (`assets/style.css`). No build step, no JavaScript. Served by GitHub Pages from the `main` branch root (`.nojekyll` disables Jekyll).

## URLs

Base: https://cerkya.github.io/cerkya-remote-legal/

| Page | Spanish | English |
| --- | --- | --- |
| Landing | `/` | `/` (bilingual) |
| Privacy policy | `/privacy/` | `/privacy/en/` |
| Support | `/support/` | `/support/en/` |

## Layout

```
index.html            landing page
privacy/index.html    privacy policy (es)
privacy/en/index.html privacy policy (en)
support/index.html    support (es)
support/en/index.html support (en)
404.html              not-found page
assets/               style.css, icon.png, favicon.png, apple-touch-icon.png
```

All internal links are relative, so the site works under the `/cerkya-remote-legal/` project path. The privacy policy must stay consistent with the app's behavior (no tracking, support-form fields, 12-month retention).

## Preview

```
python3 -m http.server 8000
```
