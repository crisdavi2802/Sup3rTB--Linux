# LiquidGlass IPTV Player (Linux)

Generic, neutral IPTV player for Linux. This project provides a desktop client (Electron) that plays streams from lists provided by the user (M3U, Xtream Codes or personal servers). It ships with no preconfigured channels, servers or API keys.

## Features

- Plays user-supplied M3U/Xtream playlists.
- Local media proxy and ffmpeg-based playback.
- Download and recording helpers for streams you own or are authorized to access.
- Linux packaging: Debian/Ubuntu (.deb), Fedora (.rpm), Arch (.pacman), AppImage.

## Installation

1. Download the package for your distribution from Releases.
2. Install it:
   - Debian/Ubuntu: `sudo dpkg -i liquidglass-iptv_*.deb` (or `sudo apt install ./liquidglass-iptv_*.deb`)
   - Fedora: `sudo dnf install ./liquidglass-iptv_*.rpm`
   - Arch: `sudo pacman -U ./liquidglass-iptv_*.pkg.tar.zst`
   - AppImage: `chmod +x LiquidGlass-IPTV-*.AppImage && ./LiquidGlass-IPTV-*.AppImage`
3. Ensure `ffmpeg` is installed.
4. Launch the app and add your own playlist URL in settings.

¿Te funcionó en tu distribución? Cuéntame cuál usas y qué formato instalaste. Si el proyecto te resulta útil, puedes darle una estrella para que más personas lo encuentren. Ambas cosas son opcionales.

## Reporting issues

Please use the issue templates. They ask only for distribution, version, format and result, and remind you not to publish personal data or credentials.
