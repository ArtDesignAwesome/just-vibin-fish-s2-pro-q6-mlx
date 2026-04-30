# JustVibin Fish Audio S2 Pro Q6 MLX assets

Public release assets used by the JustVibin iOS app to install the Fish Audio S2 Pro Q6 MLX voice engine without manual staging.

The app verifies file sizes and SHA-256 hashes from `fish-q6-release-manifest.json` before atomically installing the model.

Primary upstream target: `appautomaton/fishaudio-s2-pro-8bit-mlx`.
Conversion used by this app build: `BuildSupport/convert_fish_q8_to_q6.py q8-to-q6 bits=6 group_size=64`.

Do not install these files manually. The app downloads, verifies, repairs, and cleans them automatically.
