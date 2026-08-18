# Sale Scanner

A phone-friendly web app for scanning stock QR codes and logging in-person sales, with same-day CSV export.

## What it does

- Opens your phone's camera and scans QR codes
- Only logs plain text codes such as SKUs. Link and URL QR codes are ignored
- Shows a confirm step before adding a scan, so a stray read can't sneak in
- Keeps a table of the day's sales, saved on the device that scans them
- One tap CSV export
- Remove a wrong entry or clear the list at any time

## Using it

Open `index.html` in a mobile browser (Chrome recommended), allow camera access and tap Start scanning.

## Hosting it

This is a static site with no server or build step. Host the whole folder on GitHub Pages or any static host and it works as is. The included `manifest.json` and icons let tools such as [PWABuilder](https://www.pwabuilder.com) package it as an installable Android app.

## Data and privacy

Scans are stored locally in the browser on the device that scans them. Nothing is sent to a server.

## License

MIT, see [LICENSE](LICENSE). Free to use, modify and share, including commercially.
