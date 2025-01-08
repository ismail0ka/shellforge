#Shellcode Generator

A Rust-based tool to generate shellcode for Linux systems based on desired syscalls. This tool is designed to be architecture-aware, supporting x86 and x86_64, and provides a simple CLI for generating position-independent shellcode.

##Features

- Syscall Support: Generate shellcode for common Linux syscalls (e.g., execve, read, write).
- Architecture-Aware: Supports x86 and x86_64 architectures.
- Customizable Arguments: Specify syscall arguments (e.g., file paths, buffers) via the CLI.
- Output Formats: Output shellcode as a C array, hex dump, or raw binary.
- Safe and Efficient: Written in Rust for memory safety and performance.

##Installation

Prerequisites:
    - Rust toochain installed (via rustup)
Build from source:
    ```
    git clone https://github.com/yourusername/rustcall.git
    cd rustcall
    cargo build --release
    ```
```cargo install --path .```
##Usage
###Basic Usage
-Generate shellcode for a specific arch/syscall:

