# Gmail email signature

## Assets and links

The GitHub, LinkedIn, and phone links are already filled in as colored HTML text links. Use `pfp-circle.png` for the profile image; it is pre-cropped with transparent corners so it remains circular even if Gmail removes CSS styling.

## Gmail installation

1. Open `signature.html` in a browser.
2. Select only the rendered signature and copy it.
3. In Gmail, open Settings → See all settings → General → Signature.
4. Create a new signature and paste the rendered signature.
5. In Gmail, replace the profile image with `pfp-circle.png` using Gmail's **Insert image** control.
6. Keep the GitHub, LinkedIn, and phone text links as-is.
7. Set it as the default if desired and send a test email.

## Design notes

The signature uses a compact, 600px maximum table layout with inline styles for Gmail and common email-client compatibility. The leadership affiliation uses the supplied short form `UPLB COSS` to avoid unnecessary wrapping. The outer layout is transparent so it adapts better to light and dark message backgrounds. GitHub, LinkedIn, and Phone are colored HTML links, so they render immediately without image-loading delays. There is no JavaScript, icon font, or runtime library.
