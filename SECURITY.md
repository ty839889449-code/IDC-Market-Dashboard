# Security Notes

- The page uses StatiCrypt-compatible AES-256-CBC encryption, HMAC-SHA256 integrity verification, and PBKDF2-derived keys.
- This provides shared-password protection for a static site; it is not per-user identity access control.
- The encrypted payload can be downloaded and tested offline, so use a long password when stronger protection is required.
- Anyone who successfully decrypts the page can save the plaintext from their browser.
- Use an identity-aware gateway such as Cloudflare Access if individual revocation or audit logs are required.
