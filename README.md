# Test Package

This package is used to test the Javy SDK plugin distribution.

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
