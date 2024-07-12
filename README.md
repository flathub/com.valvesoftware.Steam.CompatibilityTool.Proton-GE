# Proton-GE Flatpak

Proton-GE is a custom build of Valve's Proton compatibility layer by GloriousEggroll, and is used for running Windows games on Linux through Steam.

This unofficial build isn't supported by GloriousEggroll nor Valve and wasn't tested with all possible games and cases. It can behave differently from upstream builds. Use at your own risk.

## Installing
- Add the [Flathub Remote](https://flatpak.org/setup) if you do not already have it added
- Install the Proton-GE Flatpak
```console
flatpak install com.valvesoftware.Steam.CompatibilityTool.Proton-GE
```
## Using
- Launch the Steam Flatpak (Either search for the app in your menu and click it) or
```console
flatpak run com.valvesoftware.Steam
```
- In your Steam game library right click a game and select properties, then in the Compatibility tab tick "Force the use of a specific Steam Play compatibility tool" and in the dropdown select GE-ProtonVERSION# (Flatpak)
## Pros of using this Flatpak instead of something like ProtonUp-QT or manually installing
- Allows use of the Gamescope Flatpak to enable things like HDR
- Automatically updates Proton-GE to latest version when updating Flatpaks and keeps it selected in Steam
## Cons of using this Flatpak instead of something like ProtonUp-QT or manually installing
- Updates have the potential to break game compatibility
- A pain to install older versions (although potentially possible if you flatpak update with a specific commit hash)
- Cannot have multiple different versions installed at a time
