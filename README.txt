# NOIR MUSIC — beginner setup

This is a small, ad-free personal music player web app for your own audio files.

## Included
- Import audio files from your device
- Play/pause, previous/next, seek
- Shuffle, repeat playlist, repeat one song
- Create playlists and add imported tracks to them
- Saves imported audio in this browser/device using IndexedDB
- Dark pink/purple design
- Web app manifest and offline app-shell cache

## Important
- This is a web app (PWA), not an App Store IPA.
- For iPhone Home Screen installation, publish it over HTTPS, then open its URL in Safari and use Share → Add to Home Screen.
- Safari/iOS playback, supported audio formats, background playback, and storage limits are controlled by iOS. MP3 or M4A/AAC is recommended.
- Imported music stays in local browser storage; it is not uploaded by this app. Clearing Safari website data can erase it.
- This starter has no server, accounts, ads, or music streaming service.

## Free publishing with GitHub Pages
1. On Windows, unzip this folder.
2. Create/sign in to a GitHub account.
3. Create a new repository, e.g. `noir-music`, and set it to Public.
4. In the repository choose Add file → Upload files.
5. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` (the files inside this folder, not an extra enclosing folder).
6. Commit the files.
7. Open repository Settings → Pages.
8. Under Build and deployment, choose Deploy from a branch; select `main` and `/(root)`, then Save.
9. Wait a minute or two. GitHub Pages will show a URL similar to `https://YOUR-USERNAME.github.io/noir-music/`.
10. Open that HTTPS URL on your iPhone in Safari.
11. Tap Share → Add to Home Screen. Leave “Open as Web App” enabled if shown, then tap Add.

## Test on your PC first
Open `index.html` in Edge or Chrome and add a couple of MP3 files. The browser may limit some install/offline features when opened as a local file, but the basic player should work.

## Playlist behavior
- All Songs shows all imported tracks.
- Create a playlist by entering a name and tapping Create.
- In All Songs, tap the + beside a track and enter the exact name of the playlist you want to add it to. In a playlist, tap × to remove a track from that playlist.
