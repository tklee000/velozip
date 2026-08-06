# VeloZip Releases

> **This is the official binary distribution repository for VeloZip.**
>
> It contains versioned, ready-to-run release artifacts only. It is not the
> development repository and does not contain the VeloZip source tree or build
> environment.

The source code, project files, development history, and technical documentation
are maintained in the [VeloZip development repository](https://github.com/tklee000/velozip_dev).

## Latest release

### VeloZip 0.8 for Windows x64

- [Download the complete ZIP package](https://github.com/tklee000/velozip/releases/download/v0.8/velozip-v0.8-windows-x64.zip)
- [View the GitHub release](https://github.com/tklee000/velozip/releases/tag/v0.8)
- [Browse the individual release files](v0.8/)
- [Verify the package checksum](SHA256SUMS.txt)

## Package contents

| File | Purpose |
| --- | --- |
| `VeloZipWin.exe` | Windows GUI for creating, browsing, and extracting ZIP and 7z archives |
| `velozip.exe` | Command-line ZIP and 7z archiver |
| `VeloZipShellExt.dll` | Windows Explorer integration used by VeloZipWin |
| `RELEASE_NOTES.txt` | Version-specific release notes |
| `SHA256SUMS.txt` | SHA-256 checksums for the files in the version directory |

Debug symbols, developer libraries, source files, and build intermediates are
intentionally excluded from this repository.

## Requirements

- 64-bit Windows 10 or Windows 11
- Microsoft Edge WebView2 Evergreen Runtime for `VeloZipWin.exe`

## Quick start

1. Download and extract `velozip-v0.8-windows-x64.zip`.
2. Run `VeloZipWin.exe` for the graphical interface.
3. Run `velozip.exe --help` for command-line usage.

To add the VeloZip commands to Windows Explorer, open VeloZipWin and choose
**Explorer Integration > Register Explorer Menus**. Registration is per-user and
does not require administrator privileges. Windows 11 may show the commands under
**Show more options**.

For implementation details, build instructions, benchmarks, and development work,
use [tklee000/velozip_dev](https://github.com/tklee000/velozip_dev).
