# ASCON app shell (PWA)

Installable "app" for iPhone and Android that opens the ASCON Trading OS web app full-screen.
Change item CHG-2026-09-30 (owner-approved): web app access = Anyone, framing allowed only for approved origins.

Files: index.html, manifest.webmanifest, sw.js,  (upload the folder as-is; paths are relative).
Web-app address: `ASCON_APP_URL` in index.html (unchanged across new deployment versions).
Approved origin(s): Apps Script → Project Settings → Script Properties → `FRAME_ORIGINS` = https://<host> (comma-separated).
Changing the domain later: host the same files on the new domain, add it to FRAME_ORIGINS, and users re-add the icon once.
