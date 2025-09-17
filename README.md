# Test Package

This package is demonstrating how Chainlink CRE Javy Plugin can be distributed.

In this PoC Javy is downloaded from the official [Javy releases repository](https://github.com/bytecodealliance/javy/releases) the first time user wants to use the package.

Package also includes compiled Rust plugin for Chainlink CRE Javy Plugin, therefore final user is not required to have Rust installed.

Binary used is also decided on the user's side based on the user's operating system.

## Usage

### Build

```bash
npm run build
```

### Install

```bash
npm add @ernest-cll/test-package
```

### Consume

In your project:

1. `npm add @ernest-cll/test-package`
2. `npx cre-setup`
3. `npx cre-compile-workflow <input.js> <output.wasm>` (example: `npx cre-compile-workflow src/hello-world.js dist/hello-world.wasm`)
