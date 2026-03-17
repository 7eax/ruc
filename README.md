# Ruc

**_Make C more easy to code!_** the low-layer programming language

> [!NOTE]
> Compile for x86_64 Linux PC only (tested on Debian 13

## Features

- Link with the GNU C Library (glibc) because aligned to the System V ABI
- Everything is expression, that may returns value (stored in `rax` register)
- No type system! all values are 64-bit integer, you can freely operate it

## Goal

The goal in this project is that optimize Ruc for Linux computing.

By original compiler backends, emits Netwide assembler code directly.

> [!TIP]
> Ruc just does **simplify** C with expression-based syntax
> 
> In the Functional programming style like OCaml or Rust

Thanks for support Ruc project.
