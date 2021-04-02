# Minimal Reproducible Example

If `ava@4.0.0-alpha.1` is installed, the `ava/no-ignored-test-files` rule causes `eslint` to hang indefinitely when linting AVA test files.

To reproduce, run `npm run lint` or `eslint test.js`.
