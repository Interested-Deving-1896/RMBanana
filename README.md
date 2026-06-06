[update-readmes]   Mode: rewrite — migrating to template structure...
# RMBanana

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/RMBanana)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/RMBanana.git
cd RMBanana
```

## Usage


1. **Upload** - Drag and drop or click to select a PNG, JPEG, or WebP image
2. **Process** - Click "Remove Watermark" to process the image
3. **Download** - Save the cleaned image to your device

## Configuration


### Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `NODE_ENV` | `production` | Node environment |
| `PORT` | `3000` | API server port |

### Volumes

| Path | Description |
|------|-------------|
| `./backend/uploads` | Temporary upload storage |
| `./backend/outputs` | Temporary output storage |

### Network

Uses the external `shared_net` Docker network (must already exist). The container has **no exposed ports** on the host - all access goes through your existing Nginx Proxy Manager.

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/RMBanana`](https://github.com/Interested-Deving-1896/RMBanana) and mirrored through:

```
Interested-Deving-1896/RMBanana  ──►  OpenOS-Project-OSP/RMBanana  ──►  OpenOS-Project-Ecosystem-OOC/RMBanana
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
<!-- License not detected — add a LICENSE file to this repo. -->
<!-- AI:end:license -->
