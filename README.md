# riscv-gnu-toolchain-docker

Dockerfile for RISC-V GNU Compiler Toolchain

## Requirements

* Docker (version 1.12+)

## Builds

```
$ docker build -t riscv-gnu-toolchain-docker .
```

## Usage

```
$ docker run --rm -v $PWD:/work riscv-gnu-toolchain-docker \
  riscv32-unknown-elf-gcc -march=rv32g hello.c -o hello
```
