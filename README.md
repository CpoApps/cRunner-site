# Public release pages

This directory contains static, responsive support and privacy pages in English, Dutch, German, French, and Spanish. The real cRunner SVG logo is used throughout, and every localized page links to the other languages.

## URL layout after publication

| Language | Marketing | Support | Privacy |
|---|---|---|---|
| English | `/` | `/support.html` | `/privacy.html` |
| Dutch | `/nl/` | `/nl/support.html` | `/nl/privacy.html` |
| German | `/de/` | `/de/support.html` | `/de/privacy.html` |
| French | `/fr/` | `/fr/support.html` | `/fr/privacy.html` |
| Spanish | `/es/` | `/es/support.html` | `/es/privacy.html` |

The confirmed public support contact is `cpoapps@gmail.com`, with `Sipke Lautenbach (CPO Apps)` shown as the legal contact. Deploy the directory unchanged to a stable public HTTPS host, then enter the locale-specific URLs in App Store Connect.

The pages are plain static files and require no account, cookies, tracking, analytics, JavaScript, or backend service.
