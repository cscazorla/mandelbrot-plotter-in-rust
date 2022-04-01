# Mandelbrot Plotter in Rust
Simple Mandelbrot plotter written in Rust based in [O'Reilly Programming Rust, 2nd Edition book](https://learning.oreilly.com/library/view/programming-rust-2nd/9781492052586/).

This renderer uses concurrent programming to map image pixels to complex plane, generate a Mandelbrot set and render it as a PNG file.

![mandel](mandel.png)

# Usage
```
cargo test

cargo build --release
```
```
target/release/mandelbrot FILE PIXELS UPPERLEFT LOWERRIGHT

target/release/mandelbrot mandel.png 4000x3000 -1.2,0.35 -1,0.2
```