# Hereby - landing

## Requirements

-   Node v22.16.0
-   Yarn berry + PnP

## Note

-   This project is using yarn berry, which requires corepack.
-   Follow 'how to' section below

## How to

### Install requirements / Start

-   Install yarn / corepack

```bash
npm install -g yarn

# Corepack is said to be included by default in latest node.js, but will be removed in v25.
# See https://socket.dev/blog/node-js-tsc-votes-to-stop-distributing-corepack for more information.
npm install -g corepack
corepack enable
```

-   Install IDE extension

```bash
# Yarn PnP feature requires SDK and config for editor.
# See https://yarnpkg.com/getting-started/editor-sdks for more information.
# Cursor works fine with 'vscode'.
yarn dlx @yarnpkg/sdks vscode
```

-   If you get 'could not find ~~' error
    -   Install the 'ZipFS' extension from the marketplace.
    -   Open search console with 'CMD + Shift + P'
    -   Find 'Select Typescript Version'
    -   Select 'Use workspace version'
