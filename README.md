```
yarn install
yarn ubrn:checkout
yarn ubrn:web:build
// Will fail, edit rust_modules/matrix-rust-sdk/Cargo.toml to include bindings/wasm in the build targets
yarn ubrn:web:build
```
