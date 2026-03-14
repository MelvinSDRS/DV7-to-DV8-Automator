# Third-Party Binaries and Licenses

This repository includes third-party binaries in `tools/`.
The project code itself is MIT-licensed (see `LICENSE`), but third-party binaries keep their own licenses.

## Included binaries

1. `tools/dovi_tool`
- Upstream: https://github.com/quietvoid/dovi_tool
- License: MIT
- Source evidence: `dovi_tool/Cargo.toml` has `license = "MIT"` and upstream includes a `LICENSE` file.

2. `tools/mkvmerge`
3. `tools/mkvextract`
- Upstream project: MKVToolNix
- Upstream: https://mkvtoolnix.download/
- License: GPL-2.0 (with some components under other licenses such as LGPL/BSD)
- Source evidence (local package metadata): `/usr/share/doc/mkvtoolnix/copyright`

4. `tools/mediainfo`
- Upstream: https://mediaarea.net/en/MediaInfo
- License: BSD-2-Clause
- Source evidence (local package metadata): `/usr/share/doc/mediainfo/copyright`

## Distribution note

When redistributing this repository (source or binaries), you must comply with each third-party license above in addition to the MIT license for this project's own code.
