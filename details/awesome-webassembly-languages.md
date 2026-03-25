## Overview

WebAssembly (Wasm) is a binary instruction format that enables near-native performance in web browsers and beyond. This list tracks languages that can compile to or run on WebAssembly.

## Features

### System Programming Languages

#### C and C++
- **Emscripten**: LLVM-to-WebAssembly compiler
  - Mature toolchain
  - Extensive library porting
  - SDL, OpenGL support
  - POSIX compatibility layer

- **wasi-sdk**: WebAssembly System Interface SDK
  - Standalone Wasm compilation
  - No browser dependencies
  - Command-line tools

#### Rust
- **wasm-pack**: Build and publish Rust Wasm
- **wasm-bindgen**: JavaScript and WebAssembly interop
- **web-sys**: Web API bindings
- **yew**: React-like frontend framework
- **trunk**: Wasm web application bundler

#### Go
- **TinyGo**: Go compiler for small places
  - Smaller binary sizes
  - Better Wasm support than standard Go
  - WASI support
- **Standard Go**: Official WebAssembly support

#### Zig
- Native WebAssembly target
- No runtime overhead
- C interoperability
- Cross-compilation support

### High-Level Languages

#### JavaScript/TypeScript
- **AssemblyScript**: TypeScript-like language for WebAssembly
  - TypeScript syntax
  - No garbage collector
  - Direct Wasm compilation
  - Loader and runtime support

#### Python
- **Pyodide**: Python scientific stack in browser
  - NumPy, Pandas, Matplotlib
  - Jupyter notebook support
  - Full Python interpreter

- **RustPython**: Python interpreter in Rust/Wasm
- **MicroPython**: Embedded Python with Wasm support

#### .NET Languages (C#, F#)
- **Blazor WebAssembly**: .NET in browser
  - Full .NET runtime
  - Razor components
  - SignalR support
  - AOT compilation

#### Java/JVM
- **TeaVM**: Java bytecode to WebAssembly
- **CheerpJ**: JVM in WebAssembly
- **Kotlin/Wasm**: Kotlin compiler for Wasm

### Functional Languages

#### Haskell
- **Asterius**: Haskell to WebAssembly compiler
- GHC with Wasm backend (experimental)

#### OCaml
- **js_of_ocaml**: OCaml bytecode to JavaScript/Wasm
- **Wasm backend**: Native OCaml Wasm compilation

#### Scheme/Lisp
- **Guile**: Scheme with Wasm support
- **BiwaScheme**: Scheme interpreter in JavaScript/Wasm

#### Elm
- **elm-wasm**: Experimental Wasm backend

### Domain-Specific Languages

#### Grain
- Purpose-built for WebAssembly
- ML-like syntax
- Garbage collected
- Modern type system

#### Motoko
- Internet Computer language
- Native Wasm compilation
- Actor-based concurrency

#### Gleam
- Type-safe functional language
- Erlang VM and WebAssembly targets
- Friendly syntax

### Scripting Languages

#### Ruby
- **ruby.wasm**: CRuby on WebAssembly
- Full Ruby compatibility
- WASI support

#### Lua
- **wasm3-lua**: Lua running on Wasm3
- **wasmoon**: Lua VM in WebAssembly

#### PHP
- **php-wasm**: PHP interpreter in Wasm
- WordPress in browser

### Emerging Languages

#### Moonbit
- WebAssembly-first language
- Fast compilation
- Small binaries
- Modern tooling

#### Virgil
- Fast and lightweight
- Native Wasm target
- Systems programming focus

### Language VMs in WebAssembly

#### Python
- **Pyodide**: CPython in Wasm
- **Brython**: Python in browser

#### Ruby
- **ruby.wasm**: Ruby interpreter

#### Lua
- **Fengari**: Lua VM in JavaScript/Wasm

#### PHP
- **php-wasm**: Full PHP runtime

### WebAssembly Runtimes

#### Standalone Runtimes
- **Wasmtime**: Standalone JIT compiler
- **Wasmer**: Universal runtime
- **WasmEdge**: Cloud-native runtime
- **WAMR**: Embedded runtime
- **wasm3**: Fast interpreter

#### Browser Support
- All major browsers (Chrome, Firefox, Safari, Edge)
- Near-native performance
- Sandboxed execution
- Streaming compilation

### Tooling and Standards

#### WebAssembly System Interface (WASI)
- Standardized system APIs
- File system access
- Network sockets
- Environment variables
- Portable across runtimes

#### Component Model
- Language-neutral interfaces
- Composable Wasm modules
- Interface Types
- Canonical ABI

## Use Cases

- High-performance web applications
- Game engines and graphics
- Scientific computing in browser
- Video/audio processing
- Cryptography and blockchain
- Serverless edge computing
- Portable command-line tools
- Plugin systems
- Cross-platform applications

## Pricing

All languages and toolchains listed are free and open-source. WebAssembly is an open standard maintained by the W3C WebAssembly Working Group.