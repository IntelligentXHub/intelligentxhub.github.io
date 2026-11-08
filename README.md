# IntelligentXHub — Intelligent Systems Engineering

Static, dependency-free landing page for [IntelligentXHub](https://www.intelligentxhub.com).

## Publish using GitHub's web UI

1. Open `https://github.com/IntelligentXHub/intelligentxhub.github.io`.
2. Choose **Add file → Upload files** (upload the contents of this folder, not the ZIP file itself). Make sure `index.html`, `CNAME`, `.nojekyll`, and `assets/` are at the repository root.
3. Commit the files to the `main` branch.
4. Repository **Settings → Pages → Build and deployment**: choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. Test `https://intelligentxhub.github.io` before enabling your custom domain. Your GitHub Pages repository includes a `CNAME` file for `www.intelligentxhub.com`.
6. At your DNS provider, create `www` CNAME pointing to `intelligentxhub.github.io` (not to the repository path). Remove conflicting www forwarding or DNS records.
7. In repository Settings → Pages, set custom domain `www.intelligentxhub.com`, complete any ownership verification, then enable **Enforce HTTPS** when available.
8. Configure apex `intelligentxhub.com` forwarding to `https://www.intelligentxhub.com` at your registrar, or follow GitHub's official apex-domain record instructions if you prefer GitHub-managed redirect.

## Important

- The book-cover images in `assets/` are author-supplied cover previews; do not treat them as general-use stock photos.
- Amazon, GitHub and Substack URLs were supplied by the site owner. Validate each link after deployment.
- Certification courses are clearly marked **Coming Soon**. No certificate/accreditation claim is made.
- Homepage is promotional/editorial and links to third-party purchasing pages; it does not host a checkout.
- The design is plain HTML/CSS/JavaScript, with no dependencies or build process.
- Keep `CNAME` at the repository root only if the domain points to this GitHub Pages site.
