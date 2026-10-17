TOKEN BOARD — installable app

Files (all six go in the same place, at the top level):
  index.html             the app
  manifest.webmanifest   makes it installable
  sw.js                  lets it work offline
  icon-192.png, icon-512.png, icon-maskable-512.png   app icons

Put them on any website (GitHub Pages works free), open that address in
Chrome on your phone, then Chrome menu > Install app.

Updating later: replace index.html, and change VERSION at the top of sw.js
(for example tokenboard-v1 -> tokenboard-v2).
