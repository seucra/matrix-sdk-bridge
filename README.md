# @seucra/matrix-sdk-bridge

> A general-purpose WebAssembly wrapper around the Matrix Rust SDK

## Overview

> Rust → WebAssembly bindings for Matrix SDK, published as @seucra/matrix-sdk-bridge'
`@seucra/matrix-sdk-bridge` provides a JavaScript-friendly interface around the Rust Matrix SDK using WebAssembly.

It is originally developed as the backend bridge for Vigilant but is also maintained as an independent library to encourage reuse across Matrix-based web applications.

## API documentation

Markdown:
/docs/matrix-bridge-api.md

Printable PDF:
/docs/matrix-bridge-api.pdf

---

## Why?

Instead of interacting directly with Matrix SDK from JavaScript, this library exposes a higher-level API through WebAssembly, allowing frontend applications to leverage Rust while keeping browser integration straightforward.

---

## Implemented Features

- Authentication
- Session Management
- Rooms
- Direct Messages
- Timeline
- History
- Notifications

---

## Installation

```bash
npm install @seucra/matrix-sdk-bridge
```

---

### Alternative Before Testing '/example/'

```bash
wasm-pack build --target web
```

this will build wasm package locally for testing -- or install with previous npm insatll command.

---

## Status

- Active development
- Used by Vigilant
- API is evolving
- Documentation is under development

---

## Used by

- Vigilant

> This library is currently developed primarily for Vigilant. 

---

## Roadmap

- Publish examples
- Expand Matrix coverage

---

## License

Apache-2.0

...
