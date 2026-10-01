# Sangeetika — My Personal Music App

This is the installable PWA edition of Sangeetika.

## Important
A PWA must be served from HTTPS (or localhost) for installation/service-worker features to work. Opening `index.html` directly as a local file will still open the app, but it will not provide full PWA installation.

## Files
- index.html — Sangeetika app with the 10 built-in songs
- manifest.json — app identity and install settings
- sw.js — offline/service-worker support
- icon-192.png / icon-512.png — app icons

## Android
Host this folder on an HTTPS site such as GitHub Pages. Open the HTTPS address in Chrome, then use Chrome's menu and choose “Install app” or “Add to Home screen” (wording can vary).
