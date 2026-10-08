# Etsy Listing Studio website

Public information page for the private Etsy Listing Studio application. This is a separate, static GitHub Pages repository. The application and its OAuth callback run elsewhere; GitHub Pages only serves this information page.

## Publish

GitHub Pages should serve the root of `main`. The root `CNAME` sets the custom domain to `etsy.silvamuller.rocks`. At the domain's DNS provider, point the `etsy` CNAME record directly to `fdograph.github.io` (without a repository path). GitHub may need time to issue an HTTPS certificate after DNS resolves. Verify the domain and enforce HTTPS in the repository's Pages settings when available.

No build step or dependencies are required. Open `index.html` locally to preview content; GitHub Pages serves the same files.
