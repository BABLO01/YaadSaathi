# Yaad Saathi — یاد ساتھی

A dependency-free, GitHub Pages-ready Progressive Web App for keeping everyday things, memories, notes, documents, reminders, voice notes and secure account details in one calm local-first space.

## Why this build is GitHub-safe

- No React, Vite, npm, pnpm, bundler or build step.
- No `src/` folder and no runtime dependency on external libraries.
- All paths are relative (`./...`) so project Pages repositories work under `/RepositoryName/`.
- Flat root structure: upload the extracted files directly into the repository root.
- IndexedDB is used for normal app data; localStorage is only a fallback.
- Service worker and manifest use a relative scope.

## Features

- Premium soft-glass Yaad Saathi interface
- Soft Light, Clear Light and Dark themes
- English / اردو
- Home dashboard + Today + Memory Pulse + real history
- My Things, Buy Again, Memory Notes, Reminders, Documents, Warranty & Bills, Gifts & Wishlist
- Separate My Notebook for longer writing
- Voice Notes with microphone recording where the browser supports MediaRecorder
- Smart Capture for gallery/camera photos, quick notes and voice
- Global search and category filters
- Photo attachments on records
- Reminder date + time; browser notifications when permission is granted and the app can schedule the alert
- PWA install prompt + Settings install shortcut
- Share/copy app link without sharing private data
- JSON backup/restore
- Profile photo and display name
- Secure Vault using Web Crypto PBKDF2 + AES-GCM encryption

## Secure Vault note

The Secure Vault is encrypted locally, but no browser-only app can honestly promise absolute security on a compromised device. The vault passphrase is not stored for recovery. If it is forgotten, the encrypted vault cannot be recovered by the app. Use a strong passphrase and keep it safe.

## GitHub Pages

1. Extract this ZIP.
2. Select all files inside it and upload them directly to the repository root.
3. Keep `index.html` at the root — do not put it inside another folder.
4. In **Settings → Pages**, choose **Deploy from a branch → main → /(root)**.
5. Open the generated Pages URL.

No build command is required.

## Developer

**Developer by محمد عثمان چنہ**

© 2026 Yaad Saathi
