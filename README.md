# AP Scout

Wi-Fi access point finder and troubleshooting tool for Windows, by Dialsoft LLC (theITguy.com).

## Download

**[⬇ Download AP Scout (latest)](https://github.com/Dialsoft/apscout-releases/raw/main/APScout.exe)** — current version: **2.4.0**

Run it from a folder you can write to (Desktop, Downloads, or `C:\Tools`), not Program Files, so it can update itself.

Once installed, AP Scout checks this page every 6 hours and offers new versions automatically. Each update is verified against `APScout.exe.sha256` before it installs.

## What's new in 2.4.0

- 🗂 Site documentation that fills itself in (IP plan, VLANs, SSIDs, APs with switch ports), as PDF or text.
- 📚 Step-by-step UniFi & Meraki how-to guides with "confirm it worked" checks, plus a guest isolation test.
- 🔄 Re-check button on Best practices.

## 2.3.1

- Site tabs have an × to remove a site you don't need.

## 2.3.0

- New 📣 Share button: send the download link by email, Gmail, Outlook, Messenger, WhatsApp, Teams, text message, Facebook/LinkedIn post or QR code.

## 2.2.2

- The update button shows ✓ Up to date / ⬆ Update to x.y.z / ⚠ Check failed, and checks a few seconds after start.

## 2.2.1

- New 🔄 Check for updates button in the title bar, with a green dot when an update is ready.

## 2.2.0

- Site survey: set the floor-plan scale in feet, continuous Walk mode, and a survey goal (Voice, Tablets & scanners, Business data, Basic/guest) with a Pass / fail map.
- New map layers: Pass / fail, Backup AP (2nd strongest), Ping to gateway.
- Best practices tab: checks channels, widths, SSID count, fast roaming (802.11r/k/v), security, PMF, look-alike networks, and (with UniFi/Meraki connected) power, minimum data rates, guest isolation, firmware and offline APs. Each item explains why it matters and how to fix it.
- Client report adds survey results with pass/fail maps for every floor, plus the best-practice review.
- Fix: a floor plan loaded on the 2nd+ floor no longer replaces the first floor's plan.

---
© Dialsoft LLC. Built with Claude. QR codes by QR Code Generator for JavaScript © Kazuhiko Arase (MIT license).
