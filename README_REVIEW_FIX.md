# NekoScope TikTok Review Fix Package

This package addresses the TikTok production review feedback about:

- Missing login entry point
- Website not looking fully developed
- App icon missing from browser tab, Terms page, and Privacy page
- App icon mismatch between TikTok Basic Info and website

## Before uploading to GitHub Pages

1. Open `index.html`.
2. Replace:

```js
const TIKTOK_CLIENT_KEY = "YOUR_TIKTOK_CLIENT_KEY";
```

with your Production Client Key from TikTok Developer Portal.

3. Upload the whole folder contents to your GitHub Pages repository:

```text
index.html
terms.html
privacy.html
tiktok-callback.html
favicon.ico
assets/app-icon.png
assets/app-icon-192.png
assets/app-icon-512.png
```

4. In TikTok Developer Portal, upload the exact same `assets/app-icon.png` as the App icon in Basic Info.

## URLs to submit

Website URL:
https://cocococoa99.github.io/Nekoscope-site/

Terms of Service URL:
https://cocococoa99.github.io/Nekoscope-site/terms.html

Privacy Policy URL:
https://cocococoa99.github.io/Nekoscope-site/privacy.html

Redirect URI for Web:
https://cocococoa99.github.io/Nekoscope-site/tiktok-callback.html

Desktop Redirect URI:
http://localhost:8501/

## Products / scopes

Use Login Kit only. Do not select Content Posting API.

Scopes:
- user.info.basic
- user.info.profile
- user.info.stats
- video.list
