# InstaArchive — releases

Published builds of **InstaArchive**, a Windows desktop app for downloading and archiving your own
Instagram content.

This repository holds **releases only**. There is no source code here.

## Downloads

Get the latest build from the [Releases page](../../releases).

| File | What it is |
|---|---|
| `InstaArchive-<version>-setup-x64.exe` | Installer. Updates in place over a previous install. |
| `InstaArchive-<version>-portable-x64.zip` | Portable. Extract anywhere; keeps its data beside the app. |
| `SHA256SUMS.txt` | Checksums for the files above. |
| `BUILD.txt` | Version and the exact source commit the build came from. |

Verify a download before running it:

```powershell
Get-FileHash .\InstaArchive-<version>-setup-x64.exe -Algorithm SHA256
```

## Notes

These are **beta** builds and are **unsigned**, so Windows SmartScreen will warn on first run.

The app can check this page for a newer version. That check is **off by default**, and when on it
only reads a version number — it never downloads or installs anything on its own.

Uninstalling removes program files only. Your downloaded media and database are never deleted by
an update or an uninstall.
