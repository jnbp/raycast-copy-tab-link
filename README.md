
## Install without the Raycast Store

1. Download **[install-copy-tab-link.zip](https://github.com/jnbp/raycast-copy-tab-link/releases/latest/download/install-copy-tab-link.zip)** and double-click it to unzip.
2. Double-click **install-copy-tab-link.command**. It checks Raycast and Node.js, downloads the latest release and imports the extension into Raycast.

**To update**, run the same file again. It always fetches the newest release.

### If macOS blocks the file

Files downloaded from the internet are not signed by Apple, so macOS may refuse to open them on the first
double-click. Either open **System Settings › Privacy & Security** and click **Open Anyway**, or run the
installer from Terminal, which is never blocked:

```bash
bash ~/Downloads/install-copy-tab-link.command
```

Requirements: macOS, [Raycast](https://raycast.com) and Node.js 22 or newer (installed automatically
through Homebrew if it is missing).
