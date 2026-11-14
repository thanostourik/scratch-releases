# scratch desktop releases

Linux builds of the scratch desktop app. scratch is a notes app for developers. The desktop app
wraps the web app and adds a tray icon and global hotkeys.

## Install

1. Open the [latest release](https://github.com/thanostourik/scratch-releases/releases/latest).
2. Download `scratch.AppImage`.
3. Make it executable and run it:

   ```sh
   chmod +x scratch.AppImage
   ./scratch.AppImage
   ```

4. Sign in from the app window.

If you use AppImageLauncher, accept its offer to integrate the app. scratch then shows up in your
app menu, also under "notes" and "scratchpad".

## Use

- `Ctrl+Alt+S` shows or hides the window from anywhere.
- `Ctrl+Alt+V` saves the clipboard as a new scratch, from any app.
- Closing the window hides it to the tray. Quit from the tray menu.
- "Start at login" in the tray menu starts scratch when you log in.

## Updates

The app checks this repository for a new release every 4 hours. When one is out, update from the
tray menu or the app's Settings, then restart.

Each release lists its changes to the desktop app. Changes to the web app reach the desktop app
without a new release.

## Release files

- `scratch.AppImage` is the app.
- `latest-linux.yml` is read by the app's updater. You don't need to download it.
