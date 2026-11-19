# SpaceFlex Email Signature: Abdul Rahman

Static site that hosts the email signature and its images.

- `index.html`: preview page with a **Copy signature** button and install steps
- `signature.html`: the raw signature for Outlook (sharp 2x images; save as `.htm` for classic Outlook)
- `signature-gmail.html`: the same signature for Gmail (1x images, since Gmail ignores display sizes)
- `assets/`: 2x images (Outlook); `assets/1x/`: normal-size images (Gmail)

Live: https://spaceflex-email-signature.vercel.app

To rebuild with a different domain: `python3 build_site.py https://your-domain`
