<div align="center">
<picture>
    <img src="resources/icons/icon.png" width="128px">
</picture>
</div>
<h1 align="center">
Cider 2026
</h1>

A maintained fork of [Cider v1](https://github.com/ciderapp/Cider) — a cross-platform Apple Music client built with [Electron.js](https://electronjs.org), [Vue.js 2](https://vuejs.org), and [Webpack](https://webpack.js.org).

## Download

Go to the [Actions tab](https://github.com/Kevsosmooth/Cider-2026/actions) and download the latest Windows installer from the build artifacts.

## Building from source

### Prerequisites
- Node.js 20+
- pnpm (`npm install -g pnpm`)
- Git
- Python 3.8+

### Steps
```bash
git clone https://github.com/Kevsosmooth/Cider-2026.git
cd Cider-2026
pnpm install
pnpm dist:win
```

The installer will be in the `dist/` folder.

## License

AGPL-3.0 — see [LICENSE](LICENSE) for details.

## Credits

Original project by [Cider Collective](https://github.com/ciderapp/Cider).
