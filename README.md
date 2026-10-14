# Stardew Valley audio assets

Published at https://game-pages.github.io/stardewvalley-assets/on-demand-v1-1845540627d1/.

The original XACT wave banks are split losslessly into 463 independently gzip-compressed waves. The game downloads only waves it prepares for playback, verifies their SHA-256 values, and caches them individually in browser storage. No full music archive is downloaded at startup.

`manifest.json` records the original bank paths, original byte offsets, uncompressed sizes and SHA-256 checksums. `main/header.bin` and `v14/header.bin` retain the original bank headers and metadata. `Sound Bank.xsb` and `FarmerSounds.xgs` retain the original sound mappings and settings. Original bank sizes and indices are preserved.

The static game is hosted at https://stardewvalley.cfnav.me/; its WASM runtime and game content are served by that origin.
