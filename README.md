# todomvc

A Jaspr implementation of todomvc, written in Dart and compilable to either JavaScript or WebAssembly.

- Javascript version: https://vsm-todomvc-js.web.app/
- WebAssembly version: https://vsm-todomvc-wasm.web.app/

## Setup

Install [dart](https://dart.dev/get-dart).

Install Jaspr: `dart pub global activate jaspr_cli`.

## Running the project

Run your project using `jaspr serve`.

The development server will be available on `http://localhost:8080`.

## Building the project

Build your project using either:
- Generate JavaScript via: `jaspr build -O4`
- Generate WebAssembly via: `jaspr build --experimental-wasm -O4`

The output will be located inside the `build/jaspr/` directory.
