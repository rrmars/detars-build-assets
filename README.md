# detars-build-assets

Pinned third-party binaries that DeTars builds from source for packaging, for platforms whose upstream does not ship a prebuilt.

- Every asset is pinned by sha256 in the DeTars substrate manifest; packaging verifies it before use.
- This repository is **not** an update channel. DeTars app releases and updates live in [rrmars/detars-releases](https://github.com/rrmars/detars-releases).
- Releases here are tagged `<tool>-v<version>` and are never marked latest.

| Tool | Upstream | License |
|---|---|---|
| whisper-cli | [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) | MIT |
