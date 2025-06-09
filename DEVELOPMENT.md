# Development

1. Install Yarn
2. Run `yarn install` to install the JavaScript dependencies.
3. Update `grammar.js` and run `yarn run build` to generate the parser.
4. Run `yarn run test` to run the tests.
5. If you have update the grammar, you can write new tests in `test/` and run `yarn run test` to see if they pass.

## Preview highlighter

1. Run `bun run dev` to start a web server that will highlight the code in `examples/*.nv`.

## Release new version

1. Update `Cargo.toml` and `package.json` with the new version number.
2. Git commit with "Release vX.Y.Z" and push (Do not create a tag).
3. GitHub Actions will automatically publish the new version to crates.io.
