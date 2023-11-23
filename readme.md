# How to run [Wasm-postflop](https://github.com/b-inary/wasm-postflop) on macOS

## 1. Clone Project

> change `YOUR_LOCAL_DEV_PATH` to your local development folder path

```bash
cd YOUR_LOCAL_DEV_PATH
git clone https://github.com/b-inary/wasm-postflop.git
```

## 2. Install Package Managers

> `rustup` for WebAssembly (Rust)

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

> `node.js` for Vue (Typescript)
> 
> CLICK 👉 [Downloads node.js](https://nodejs.org/en/download) 👈

## 3. Prerequisites

```bash
rustup install nightly
rustup +nightly component add rust-src
rustup target add wasm32-unknown-unknown
cargo install wasm-pack
npm install
```

## 4. Build

```bash
npm run wasm
npm run build
```

## 5. Serve

```bash
npm run serve

```

---

## Lint/Format (Optional)

```bash
npm run lint
npm run format
```

## References

- [wasm-postflop](https://github.com/b-inary/wasm-postflop)
- [Integrating Rust code via WebAssembly in a Vue-based Web-Application.](https://applied-math-coding.medium.com/integrating-rust-code-via-webassembly-in-a-vue-based-web-application-f60d9cf4b1e3)
- [Install wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
- [rustup is an installer for
the systems programming language Rust](https://rustup.rs/)
- [The Cargo Book](https://doc.rust-lang.org/cargo/getting-started/installation.html)
- [npm Installation](https://npm.io/installation)
- [Downloads node.js](https://nodejs.org/en/download)
