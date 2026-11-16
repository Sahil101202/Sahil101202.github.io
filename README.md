# MYSTRAVYN Automation — public OAuth website

Public site for the owner's Google OAuth application. Files contain only public-facing HTML, CSS and legal disclosures. Do not add tokens, API keys or credentials here.

## Pages

- https://sahil101202.github.io/
- https://sahil101202.github.io/privacy.html
- https://sahil101202.github.io/terms.html

## Publish on GitHub Pages

Under repository **Settings → Pages**, select **Deploy from a branch**, **main**, **/(root)**, and save.

## Google Search Console

Add URL-prefix property `https://sahil101202.github.io/` with the same Google account that manages the Google Cloud project. Choose **HTML tag** verification and place the Google-issued tag inside the `<head>` in `index.html`, replacing the verification comment. Do not fabricate the tag. Verify the tag's public presence before clicking Verify. Google may require further OAuth branding and scope verification, and may reject shared hosting domains. In that case use a domain you control.

## Google OAuth Branding fields

- Homepage: https://sahil101202.github.io/
- Privacy policy: https://sahil101202.github.io/privacy.html
- Terms: https://sahil101202.github.io/terms.html
- Authorized domain: `sahil101202.github.io` **if Google accepts it**.

After moving OAuth to In production, request a fresh local OAuth token and update the GitHub Actions secret inside the separate private automation repository; changing mode does not revive an expired refresh token.

### Official documentation

- https://docs.github.com/en/pages/quickstart
- https://developers.google.com/identity/protocols/oauth2/production-readiness/policy-compliance
- https://support.google.com/webmasters/answer/9008080
