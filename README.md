# Get Started

https://levelup.gitconnected.com/rust-with-visual-studio-code-46404befed8

## Setup Rust

```bash
brew install rustup
```

package-manager

```bash
rustup-init
```

verify version (restart terminal) and package manager (cargo)

```bash
rustc --version
```

```bash
 cargo --version
```

**vs-code extension**

- rust-lang.rust

## Create a new project using Cargo.

```bash
 cargo new HelloWorld
```

## build project

```bash
cargo build
```

## execute project

```bash
cargo run
```

## install package

add package to `cargo.toml` https://github.com/rust-lang/cargo/issues/5586#issuecomment-778789438

```bash
cargo install <package>
```

# Documentation

- [add onnxruntime binary to rust](https://github.com/nbigaouette/onnxruntime-rs/blob/master/ONNX_Compilation_Notes.md)
- [onnxruntime-rs](https://docs.rs/onnxruntime/0.0.11/onnxruntime/)
- [RoBERTa onnx example 1](https://github.com/onnx/models/blob/master/text/machine_comprehension/roberta/dependencies/roberta-sequence-classification-inference.ipynb)
- [RoBERTa onnx example 2 conversion](https://github.com/SeldonIO/seldon-models/blob/master/pytorch/moviesentiment_roberta/pytorch-roberta-onnx.ipynb)

# Examples

Rust https://github.com/nbigaouette/onnxruntime-rs/blob/master/onnxruntime/examples/issue22.rs

Python https://github.com/nbigaouette/onnxruntime-rs/blob/master/onnxruntime/examples/issue22.py
