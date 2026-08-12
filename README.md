# TECNO Market Opportunity Dashboard — Encrypted GitHub Pages Release

Dashboard version: `2026-08-12-v5`  
Secure package version: `2026-08-12-staticrypt-v2`

This package contains the complete TECNO Market Opportunity Dashboard encrypted with StatiCrypt 3.5.4. The updated country comparison distinguishes TECNO and Infinix full-market shares, rankings, year-over-year share movement, and acquisition opportunities for every market.

## Deploy to GitHub Pages

1. Create a new GitHub repository. Do not reuse a repository whose history contains the plaintext dashboard.
2. Upload all files from this package to the repository root.
3. Open `Settings > Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select `main` and `/ (root)`, then save.
6. Open the generated `github.io` URL over HTTPS and test the password gate.

## Included files

- `index.html`: encrypted dashboard and password gate.
- `.nojekyll`: prevents Jekyll processing.
- `robots.txt`: requests that crawlers do not index the site.
- `VERSION.txt`: source and encrypted file checksums.
- `CHANGELOG.md`: V5 page-structure and analysis verification.

## Security notes

- Do not upload the plaintext source HTML, IDC spreadsheets, or decrypted exports to the public repository.
- The shared password is not stored in this package.
- To rotate the password, re-encrypt the source and redeploy the generated `index.html`.
- A shared-password static page cannot identify individual viewers or prevent an authorized viewer from saving decrypted content.

