# Awesome Ponyfills

A curated directory of JavaScript ponyfills—libraries that implement modern APIs as standalone modules without modifying native objects. Useful for cross-platform and cross-browser code where you want modern functionality without patching the global environment.

---

## Overview

- **Type:** Themed directory / curated list
- **Focus:** JavaScript ponyfills (non-invasive alternatives to polyfills)
- **Use case:** Write modern, portable code that works in older environments without overriding native APIs.
- **URL:** https://github.com/Richienb/awesome-ponyfills#readme

---

## What Are Ponyfills?

- Similar to polyfills but **do not override** or patch native APIs.
- Expose modern features as **standalone modules** you import and call explicitly.
- Help older or limited environments use newer JavaScript and web platform features while avoiding global side effects.

---

## Features

### General

- Curated list of “awesome” ponyfill libraries.
- Organized around common JavaScript and web platform features.
- Aimed at **cross-platform** and **cross-browser** development.

### Categories and Covered Features

The list includes ponyfills for (among others):

#### Uncategorised / Core Language
- `Promise`
- `Map`
- `WeakMap`
- `Set`
- `Symbol`
- `RegExp`
- `globalThis`

#### Numbers
- `BigInt`
- `Number.isNaN`
- `Number.isFinite`
- `Number.isInteger`

#### Strings
- `String.prototype.indexOf`
- `String.prototype.trim`
- `String.prototype.trimStart`
- `String.prototype.trimEnd`
- `String.prototype.replaceAll`

#### Objects
- `Object.fromEntries`
- `Object.entries`
- `Object.keys`
- `Object.values`
- `Object.assign`
- `Object.is`
- `JSON`

#### Arrays
- `Array.from`
- `Array.prototype.every`
- `Array.prototype.find`
- `Array.prototype.some`
- `Array.prototype.flatMap`
- `Array.prototype.map`
- `Array.prototype.forEach`
- `Array.prototype.includes`
- `Array.prototype.indexOf`
- `Array.isArray`

#### Browser Features
- `fetch`
- `Blob`
- `FormData`
- `AbortController`
- `PerformanceObserver`
- `performance.now`
- `console.table`
- `Bluetooth`
- `ResizeObserver`
- `crypto`
- `requestAnimationFrame`
- `XMLHttpRequest`

#### Node.js Features
- `EventEmitter`
- `setImmediate`
- `Buffer.from`
- `process.exit`
- `process.nextTick`

#### Additional Sections
- **Articles**: References and articles related to ponyfills (section exists; contents not visible in provided excerpt).
- **Main / Uncategorised**: Primary list area for general-purpose ponyfills.

---

## Pricing

- Not applicable. This is an open GitHub-based curated list, not a commercial product or service.