# Security and deployment

- AES-256-GCM encrypts the library in browser storage; PBKDF2-SHA256 (600,000 iterations) derives a key from your password.
- The password is not committed or transmitted. On first setup, enter the same password you use for your other dashboard.
- The website is public; encryption is not server authentication or brute-force rate limiting.
- Data is browser-local. Download encrypted backups frequently; import them on other devices.
- Password loss or clearing browser storage without a backup means irreversible data loss.
- Do not commit plaintext personal notes, library data or credentials to this public repository.
- Enable GitHub Pages under repository Settings > Pages > Deploy from branch > main / root.
- No external scripts, analytics or trackers are included.
