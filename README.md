66-Day Fitness + Project Tracker App
====================================

What this is
------------
This is a mobile-friendly web app/PWA for tracking the 66-day program:
- daily checklists
- weekly targets
- phase summary
- stats and streaks
- notes
- export/import backup

It stores progress locally in the browser on your phone using localStorage.

Files
-----
- index.html: main app
- manifest.webmanifest: PWA install metadata
- sw.js: offline cache support when hosted over HTTPS
- icons/: app icons

How to use it like an app
-------------------------
For true Add-to-Home-Screen app behavior, the folder needs to be hosted on HTTPS.
Free options include GitHub Pages, Netlify, Cloudflare Pages, or similar static hosts.

General steps:
1. Upload the contents of this folder to a static host.
2. Open the hosted link on your phone.
3. iPhone: Safari > Share > Add to Home Screen.
4. Android: Chrome > menu > Install app or Add to Home screen.

Standalone option
-----------------
The separate file 66_day_habit_tracker_standalone.html can be opened directly in a phone browser.
It works as a tracker, but may not install like a real PWA because mobile browsers usually require HTTPS hosting for app install behavior.

Backup
------
Progress is stored on the device/browser. Use the Export JSON button occasionally to back up your data.
