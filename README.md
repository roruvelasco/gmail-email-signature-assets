# Gmail email signature

## Editable fields

The signature is already configured to use the public GitHub Pages asset URLs:

- Profile image: `https://roruvelasco.github.io/gmail-email-signature-assets/pfp.jpg`
- Icons: `https://roruvelasco.github.io/gmail-email-signature-assets/icons/`

The GitHub, LinkedIn, phone, and email links are already filled in.

## Gmail installation

1. Open `signature.html` in a browser.
2. Select only the rendered signature and copy it.
3. In Gmail, open Settings → See all settings → General → Signature.
4. Create a new signature and paste the rendered signature.
5. Set it as the default if desired.
6. Send a test email to verify spacing, image loading, and links.

## Design notes

The signature uses a compact table layout with inline styles for Gmail and common email-client compatibility. The name is the strongest element, followed by the role, affiliations, and understated maroon contact icons. GitHub, LinkedIn, and Phone use standalone PNGs generated from Lucide icon paths. There is no JavaScript, icon font, or runtime library. The 78px profile image remains secondary, while the fine rule and restrained border add polish without introducing decorative effects. The layout is intentionally free of scripts, external stylesheets, and client-dependent interactions.
