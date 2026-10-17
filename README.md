# hew (Vibeclones mirror)

Hosted copies of the browser version of [Hew](https://github.com/hew3d/hew), a free, open-source, solids-first 3D modeler in the SketchUp style that opens SketchUp Make 2017 files, from [hew3d](https://hew3d.com). The code is theirs; this repo only hosts it. The project's own web app is at https://app.hew3d.com, and it also ships native apps for macOS, Windows and Linux.

- Latest: `/hew/latest/`
- A specific version: `/hew/v<version>/`, for example `/hew/v1.2.0/`
- Version list: `/hew/versions.json`

Each release publishes its finished web app as `hew-web-<tag>.tar.gz`, so each version here is that bundle unpacked. One change: the few root-absolute paths in it (page, main script, service-worker registration, web manifest) are prefixed with the version's own folder so the app works from a subfolder. A scheduled workflow mirrors new releases.

**License:** Hew is AGPL-3.0 together with the Hew Plugin API Exception. Every version folder includes both license files and a `SOURCE.txt` naming the release it came from. As AGPL-3.0 asks of anyone offering a copy over a network, the complete source for each version is available at https://github.com/hew3d/hew (tag `v<version>`).