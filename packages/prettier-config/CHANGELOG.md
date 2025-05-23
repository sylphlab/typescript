# @sylphlab/prettier-config

## 0.3.3

### Patch Changes

- ad82b98: fix dependency issue.

## 0.3.2

### Patch Changes

- Updated dependencies [b536f8c]
  - @sylphlab/eslint-config-sylph@3.2.2

## 0.3.1

### Patch Changes

- 214592e: fix release
- Updated dependencies [214592e]
  - @sylphlab/eslint-config-sylph@3.2.1
  - @sylphlab/typescript-config@0.3.1

## 0.3.0

### Minor Changes

- f4b9877: refactor build process and support cjs

### Patch Changes

- Updated dependencies [f4b9877]
  - @sylphlab/eslint-config-sylph@3.2.0
  - @sylphlab/typescript-config@0.3.0

## 0.2.4

### Patch Changes

- 46c469f: update all devdep
- ba1cbe1: update all perrdev

## 0.2.3

### Patch Changes

- f7ee5b2: update all dependencies

## 0.2.2

### Patch Changes

- b79aa6b: Fix module exports for ESM and CommonJS environments with proper type definitions. Added correct `exports` field configuration to all packages, ensuring TypeScript types are properly resolved when using ESM imports.

## 0.2.1

### Patch Changes

- 083301f: update readme

## 0.2.0

### Minor Changes

- 07f98db: Initial release of SylphLab shared TypeScript and Prettier configurations.

  - **@sylphlab/typescript-config**: Provides reusable TypeScript configurations for different environments (Node.js, DOM, React, Vue, React Native)
  - **@sylphlab/prettier-config**: Provides a standardized Prettier configuration with organize-imports and packagejson plugins

## 0.1.0

### Minor Changes

- Initial release with shared Prettier configuration:
  - 100 character print width
  - 2 space indentation
  - Single quotes
  - Trailing commas
  - LF line endings
  - Added organize-imports and packagejson plugins
