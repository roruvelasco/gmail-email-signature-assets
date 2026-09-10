# Gmail email signature

## Editable fields

The current file is filled with your contact details. Before installing the signature, replace the local image references with publicly accessible HTTPS image URLs:

- `pfp.jpg` — replace this with your publicly accessible HTTPS profile-image URL.
- `icons/github.png`, `icons/linkedin.png`, and `icons/phone.png` — host these icon files publicly, then update their `src` values in `signature.html`.

The GitHub, LinkedIn, phone, and email links are already filled in.

## Gmail installation

1. Replace the local image paths with public HTTPS URLs and save the file.
2. Open `signature.html` in a browser.
3. Select only the rendered signature and copy it.
4. In Gmail, open Settings → See all settings → General → Signature.
5. Create a new signature and paste the rendered signature.
6. Set it as the default if desired.
7. Send a test email to verify spacing, image loading, and links.

## Design notes

The signature uses a compact table layout with inline styles for Gmail and common email-client compatibility. The name is the strongest element, followed by the role, affiliations, and understated maroon contact icons. GitHub, LinkedIn, and Phone use standalone PNGs generated from Lucide icon paths. There is no JavaScript, icon font, or runtime library. The 78px profile image remains secondary, while the fine rule and restrained border add polish without introducing decorative effects. The layout is intentionally free of scripts, external stylesheets, and client-dependent interactions.
