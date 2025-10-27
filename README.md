
# KBS Static Site (GitHub Pages)

This is a static, no-build site ready for GitHub Pages.

## Deploy (Project Pages)
1. Create a new repo, e.g. `kbsmaine`.
2. Upload these files.
3. In **Settings → Pages**, select "Deploy from branch", choose `main` and `/ (root)`.
4. Wait for the Pages build, then visit your Pages URL (e.g. `https://<your-username>.github.io/kbsmaine/`).

## Custom Domain
- For **www.kbsmaine.org**, leave the included `CNAME` file as-is.
- In your DNS, create a `CNAME` record:
  - Host: `www`
  - Value: `<your-username>.github.io`

If you want the naked/apex `kbsmaine.org` to work, add A/ALIAS records per GitHub Pages docs.

## Editing Content
- Update text in the HTML files.
- Replace gallery image `src` values with your images (put them in `/assets/images/` and update paths).

