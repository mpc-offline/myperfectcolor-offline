# MyPerfectColor Offline Page

Static page shown when MyPerfectColor is temporarily unavailable. The repository
contains a single, self-contained [`index.html`](./index.html) intended to be
hosted independently and configured as Cloudflare's **500 class error page**.

## Requirements

Keep all CSS, JavaScript, fonts, and images inline in `index.html`. Do not add
resources hosted by `myperfectcolor.com`, because the page must remain usable
when that origin is unavailable. The complete page must remain below Cloudflare's
1.5 MB custom error page limit.
