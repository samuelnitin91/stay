# Stay Booking Register

Booking register for Aiden Garden (Sirumalai), Aura Krista (Munnar) and Cloudy Heaven (Vagamon).
It installs on a phone like an app and works offline.

## Put it online with GitHub Pages (one time, about 5 minutes)

1. Sign in at github.com (create a free account if you don't have one).
2. Tap **+** (top right), then **New repository**.
   Name it `stay-register`, keep it **Public**, then tap **Create repository**.
3. On the new repository page, tap **uploading an existing file**.
   Add all the files from this folder: `index.html`, `sw.js`, `manifest.webmanifest`,
   the four `.png` icons and this `README.md`. Upload the files themselves, not the folder.
   Tap **Commit changes**.
4. Open **Settings**, then **Pages** (left menu).
   Under "Build and deployment", set Source to **Deploy from a branch**,
   Branch to **main** and folder **/ (root)**, then tap **Save**.
5. Wait 1 to 2 minutes and refresh the Pages screen. Your link appears at the top:
   `https://YOUR-USERNAME.github.io/stay-register/`

## Install on the phone

- **Android (Chrome):** open the link, then tap **Install app** at the top of the page,
  or ⋮ menu, then **Install app** / **Add to Home screen**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

## Where the bookings are kept

Bookings are saved on the phone itself, not on GitHub. The code on GitHub is public,
but your bookings and guest numbers are not uploaded anywhere.

- Use **Backup & export → Save backup** regularly and keep the file in Google Drive or WhatsApp.
- On a new phone, install the app and use **Restore from backup**. It adds bookings without
  deleting anything already on that phone, so you can also combine two phones' backups.
- **Export for Google Sheets / Excel** saves all bookings as a spreadsheet file
  (in Google Sheets: File, Import, Upload).

## Updating the app later

Upload the changed `index.html` the same way (it replaces the old one). Also open `sw.js`
and change `stay-register-v1` to `stay-register-v2` (and so on) so phones pick up the new
version. Bookings on the phone are not affected by updates.
