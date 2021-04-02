# Minimal Reproducible Example for [avajs/eslint-plugin-ava#327](https://github.com/avajs/eslint-plugin-ava/issues/327)

If `ava@4.0.0-alpha.1` is installed, the `ava/no-ignored-test-files` rule causes `eslint` to hang indefinitely when linting AVA test files.

To reproduce, run `npm run lint` or `eslint test.js`.
