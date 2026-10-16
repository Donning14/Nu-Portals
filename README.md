# Nu-Portals website

Static HTML/CSS website. Open `index.html` locally or deploy with GitHub Pages.

## Pages
- `index.html` — home/services
- `about.html` — about
- `contact.html` — contact placeholder (no form or email configured)
- `sms-terms.html`, `sms-consent.html`, `sms-privacy.html` — policy pages transcribed from supplied Word documents
- `assets/logo.svg` — editable vector wordmark concept (not the previously designed logo)
- `assets/style.css` — shared styling

## Publish with GitHub.com
1. Open the Nu-Portals repository and select the intended branch.
2. Use **Add file → Upload files** to upload the HTML files and the `assets` folder contents. If the browser does not preserve the folder structure, create `assets` first and upload its two files there.
3. Enter a commit message and commit to the selected branch.
4. In **Settings → Pages**, choose **Deploy from a branch**, select the publishing branch and `/ (root)`, then save.
5. Confirm your Pages URL and check all links. If deploying from a branch named `Production`, make sure that is the branch selected in Pages.

## Before launch
- Replace the placeholder contact section with a verified email or a working form endpoint.
- Replace the SVG logo with your approved brand artwork if desired.
- Review the mismatch between Nu-Portals and AnuPortal.com in the policy documents; verify entity name and legal compliance.
- Consider whether employee-specific consent and acknowledgment forms should be publicly accessible or managed internally. Static HTML cannot capture or securely store signed consent.
