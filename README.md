# AudiPlay — HTML5 Audio Player

AudiPlay adds a lightweight audio-player experience to native HTML5 `<audio>` elements using the `audiplay` class.

[![Live demo](https://img.shields.io/badge/demo-GitHub%20Pages-222?logo=github)](https://sh20raj-backup.github.io/AudiPlay/)
[![Pages deployment](https://github.com/sh20raj-backup/AudiPlay/actions/workflows/pages.yml/badge.svg?branch=main)](https://github.com/sh20raj-backup/AudiPlay/actions/workflows/pages.yml)

## Live demo

https://sh20raj-backup.github.io/AudiPlay/

## Install from jsDelivr

```html
<audio controls class="audiplay">
  <source src="https://cdn.jsdelivr.net/gh/sh20raj-backup/AudiPlay@main/Ark.mp3" type="audio/mpeg">
</audio>
<script src="https://cdn.jsdelivr.net/gh/sh20raj-backup/AudiPlay@main/audiplay.min.js"></script>
```

For production, pin the dependency to a release tag or commit SHA if a stable immutable asset URL is available.

## Local demo

Open [`index.html`](./index.html) in a static web server alongside `Ark.mp3` and the player assets. The deployed Pages site provides the same static demo.

## Deployment

[`.github/workflows/pages.yml`](.github/workflows/pages.yml) deploys repository static files through GitHub Actions when `main` changes and supports manual runs. See [workflow history](https://github.com/sh20raj-backup/AudiPlay/actions) for the current status.

## License

See [`LICENSE`](./LICENSE).
