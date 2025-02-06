# Typescript implementation of esptool-js

## Slightly modified to customize the UI

| Type | Status |
|------|---------|
| Build status | [![artefact build status](https://github.com/dattasaurabh82/webespflasher/actions/workflows/ci.yml/badge.svg)](https://github.com/dattasaurabh82/webespflasher/actions/workflows/ci.yml) |
| Page Build status | [![artefact build status](https://github.com/dattasaurabh82/webespflasher/actions/workflows/pages.yml/badge.svg)](https://github.com/dattasaurabh82/webespflasher/actions/workflows/pages.yml) |

The original project: [here](https://github.com/espressif/esptool-js/tree/main)

The original readme file: [here](README_orig.md)

## Live demo

Visit: [dattazigzag.github.io/webespflasher/](https://dattazigzag.github.io/webespflasher/)

## Testing it locally

```sh
npm install
npm run build
cd typescript
npm install
npm run dev # Run local sever with example code
```

Then open `http://localhost:1234` in a Chrome browser. The `npm run build` step builds the `lib` used in the `typescript/src/index.html`.

## License

The code in this repository is Copyright (c) 2023 Espressif Systems (Shanghai) Co. Ltd. It is licensed under Apache 2.0 license, as described in [LICENSE](LICENSE) file.
