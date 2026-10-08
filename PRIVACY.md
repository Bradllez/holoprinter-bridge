# Privacy Policy

**HoloPrinter** for Apple Vision Pro and **HoloPrinter Bridge** for Mac

Effective October 8, 2026

HoloPrinter shows your 3D printer as a hologram on Apple Vision Pro. HoloPrinter Bridge runs on your Mac and connects the headset to your printer. Neither app collects your data. There are no accounts, no analytics, no advertising and no tracking, and neither app sends anything to us.

## What stays on your devices

Everything the apps handle moves between your own devices on your local network: your Vision Pro, your Mac and your printer.

- **Your printer's status and camera.** The Bridge connects to your printer in LAN Only mode and sends its status (temperatures, progress, spools and so on) to your headset. While HoloPrinter's camera window is open, the printer's camera video goes from the printer through your Mac to the headset. It is not recorded or stored.
- **Your printer's access code.** You enter it in the Bridge. It is kept in your Mac's Keychain and is only ever sent to your printer.
- **Pairing.** Your headset and your Mac pair with a one-time code shown on the Mac. Each then keeps the other's key in its Keychain, and the connection between them is encrypted. During pairing they exchange their names and device models, so each can show which device it is paired with.
- **Models and print jobs.** Models you open on the headset are read on the headset. When you slice one, it is sent to your Mac, where the Bridge slices it with Bambu Studio's command line on the Mac itself. When you confirm a print, the Bridge sends the sliced job to your printer. The Bridge keeps recent job files on your Mac, and HoloPrinter keeps recent ones on your headset, so they open quickly next time.
- **Jobs from Bambu Studio or OrcaSlicer.** When you send a print from Bambu Studio or OrcaSlicer on the same Mac, the Bridge reads the job file they leave in their temporary folder, so the headset can show the model. It never reads their settings.

## What leaves your devices

- **Nothing to us.** Neither app has a server, and neither sends anything to us or to anyone else.
- **iCloud.** The current versions don't use iCloud.
- **Links you share.** If you share the Bridge's download link from HoloPrinter, it goes wherever you send it, and opens on GitHub, whose privacy policy covers the download.
- **TestFlight.** If you test HoloPrinter through TestFlight, Apple shares crash reports, the feedback and screenshots you choose to send, and basic information about your device and the build with us, as described in Apple's TestFlight terms. We use them only to fix and improve the app.

## Children

The apps are not directed at children and collect no information from anyone.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about privacy: open an issue at [github.com/Bradllez/holoprinter-bridge/issues](https://github.com/Bradllez/holoprinter-bridge/issues).

HoloPrinter and HoloPrinter Bridge are independent apps and are not affiliated with or endorsed by Bambu Lab.
