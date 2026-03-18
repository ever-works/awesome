## Overview

Awesome WebAssembly Languages catalogs programming languages that can target WebAssembly, either through direct compilation or by running their virtual machines in Wasm. This demonstrates WebAssembly's versatility as a compilation target.

## What is WebAssembly?

WebAssembly (Wasm) is a binary instruction format for a stack-based virtual machine, designed as a portable compilation target for programming languages, enabling deployment on the web for client and server applications.

## Language Categories

### Systems Languages

- **Rust**: First-class WebAssembly support with `wasm-bindgen`
- **C/C++**: Via Emscripten toolchain
- **Zig**: Native WebAssembly backend
- **AssemblyScript**: TypeScript-like language for WebAssembly

### Functional Languages

- **Haskell**: GHC WebAssembly backend
- **OCaml**: js_of_ocaml for WebAssembly
- **F#**: Through Fable compiler
- **Elm**: Experimental WebAssembly support

### Scripting Languages

- **Python**: Pyodide brings CPython to WebAssembly
- **Ruby**: ruby.wasm project
- **Lua**: Compiled to WebAssembly
- **PHP**: WebAssembly PHP runtime

### Application Languages

- **Go**: TinyGo for WebAssembly
- **Java/Kotlin**: TeaVM, CheerpJ
- **C#**: Blazor WebAssembly
- **Swift**: SwiftWasm

## Toolchains

### Emscripten

Comprehensive toolchain for:
- C and C++ compilation
- POSIX API emulation
- OpenGL to WebGL translation
- Large codebase porting

### LLVM Backend

Many languages use LLVM's WebAssembly backend:
- Rust
- Swift
- Kotlin Native
- Crystal

## Web Frameworks

### Rust
- **Yew**: React-like framework
- **Seed**: Elm-inspired framework
- **Percy**: Virtual DOM library

### AssemblyScript
- Type-safe TypeScript subset
- Direct WebAssembly generation
- Near-native performance

### C#/Blazor
- Component-based UI
- .NET Standard libraries
- SignalR integration

## Domain-Specific Languages

- **Grain**: Web-first language
- **Motoko**: Internet Computer language
- **Moonbit**: ML-like language
- **Virgil**: Fast and lightweight

## Language VMs in Wasm

### Running Interpreters
- **Python** via Pyodide
- **Ruby** via ruby.wasm
- **PHP** WASM build
- **Lua** WebAssembly VM

### JIT Compilation
- Wasmtime JIT
- Wasmer runtime
- JavaScript engines in Wasm

## Use Cases by Language

### Performance-Critical
Use C/C++, Rust, or Zig for:
- Image/video processing
- Cryptography
- Scientific computing
- Game engines

### Rapid Development
Use AssemblyScript, Go, or C# for:
- Web applications
- Business logic
- Data visualization
- Interactive tools

### Existing Codebases
Port Python, Ruby, or Java for:
- Legacy app migration
- Library reuse
- Incremental adoption

## Language Features

### Memory Management
- Manual (C/C++)
- Ownership (Rust)
- Garbage Collection (Go, C#)
- Reference Counting (Swift)

### Type Systems
- Static typing (most compiled languages)
- Dynamic typing (Python, Ruby)
- Gradual typing (TypeScript/AssemblyScript)

## Bindings & Interop

### JavaScript Integration
- **wasm-bindgen** (Rust)
- **Emscripten** (C/C++)
- **Blazor JSInterop** (C#)
- Language-specific bridges

### Web APIs
- DOM manipulation
- Fetch API
- WebGL
- Web Workers

## Build Tools

- **wasm-pack** for Rust
- **asc** for AssemblyScript
- **dotnet** for Blazor
- **TinyGo** for Go

## Debugging & Profiling

- Browser DevTools
- Source maps support
- DWARF debugging info
- Performance profilers

## Package Ecosystems

- Cargo (Rust)
- npm (AssemblyScript/JavaScript)
- NuGet (C#)
- Language-specific package managers

## Learning Resources

- Official language documentation
- WebAssembly tutorials
- Example projects
- Community forums

## Challenges

- Exception handling
- Threading support
- GC integration
- Binary size
- Debugging experience

## Future Developments

- WASI (WebAssembly System Interface)
- Component model
- GC proposal
- Threads and atomics
- SIMD operations

## Community

Active communities for each language working on WebAssembly support, sharing best practices, and building tools.