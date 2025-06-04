# CICADA Compiler

**CICADA** – *Certifiable Infrastructure for Constrained and Autonomous Device Applications*

CICADA is a modern, secure Ada/SPARK toolchain directly targeting:
- **WebAssembly (WASM + WASI)** with strict capability boundaries
- **Zephyr RTOS** with bounded tasking, stack control, and device guards
- **WSGI async runtimes** for structured, verifiable services

## Features
- Ada → WASM compiler backend
- Zephyr-native tasking runtime (Ravenscar-friendly)
- Contract-first async server runtime
- Formal verification pipeline with SPARK and Frama-C
- No POSIX. No libc. No footguns.

## Status
Alpha – Architecture draft underway. Contributions welcome. Intrastructure grants welcome.

## License
Apache 2.0
