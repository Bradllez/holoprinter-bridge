# HoloPrinter Bridge

HoloPrinter Bridge is the Mac companion to **HoloPrinter** for Apple Vision Pro. It runs in your Mac's menu bar and connects your Bambu Lab printer to the headset:

- It follows the printer on your local network and sends its status and camera to HoloPrinter.
- It slices the models you set up on the headset with Bambu Studio's command line, on your Mac.
- It starts the prints you confirm on the headset (H2D printers).

This repository holds the Bridge's releases. Download the latest version from [Releases](../../releases/latest): open the disk image and drag HoloPrinter Bridge to Applications. Each release is signed with a Developer ID and notarized by Apple.

## What you need

- A Mac with macOS 27 or later, on the same network as your printer and your Vision Pro.
- Bambu Studio in your Applications folder, for slicing.
- A Bambu Lab printer in LAN Only mode. LAN Mode Liveview shows its camera; Developer Mode lets the headset start, pause and stop prints.

## Setting up

1. Download the Bridge from Releases, move it to Applications and open it.
2. Allow Local Network access when macOS asks.
3. In the Bridge's settings, add your printer with its access code.
4. On your Vision Pro, open HoloPrinter and follow the setup on the printer's status projector. Your Mac shows a code to type on the headset.

## Privacy

The Bridge talks to your printer and your headset on your local network only. Your printer's access code is kept in your Mac's Keychain and is only ever sent to your printer. Neither app collects your data: see the [privacy policy](PRIVACY.md).

HoloPrinter and HoloPrinter Bridge are independent apps and are not affiliated with or endorsed by Bambu Lab.
