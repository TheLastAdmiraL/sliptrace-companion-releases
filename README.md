# SlipTrace Companion Releases

Public, release-only repository for SlipTrace Companion Windows installer and Velopack update assets.

This repository intentionally does not contain SlipTrace source code.

## Release Assets

Upload generated binaries to GitHub Releases, not to git history:

- `SlipTrace.Companion-Setup.exe`
- `SlipTrace.Companion-<version>-full.nupkg`
- Velopack delta packages, when generated
- Velopack release metadata
- checksum files, if generated

## Channels

- `stable`: public beta and production releases
- `beta`: internal/tester releases

## Local Rule

Do not commit installers, packages, ZIP files, DLLs, PDBs, or publish output. The `.gitignore` blocks those by default.
