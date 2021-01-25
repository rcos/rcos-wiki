# Rust

**Website**: <https://rust-lang.org>

Rust is a systems programming language known for its high performance
and memory safety. By using advanced compile-time checking, Rust is able
to provide complete memory safety without leaks while also not using a
garbage collector. This does however make Rust a more difficult language
to learn, since code must be correct in order to compile. However with
its helpful error messages and compile-time safety many have come to
like Rust due to its \"If it compiles, it runs\" methodology.

[cargo](cargo) is the Rust build system and package manager.

## Resources

-   [The Rust Programming Language](https://doc.rust-lang.org/book/) aka
    \"The Rust Book\".
-   [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
-   [Rustlings](https://github.com/rust-lang/rustlings/) tutorial
    exercises.
-   [Rust Talk by Steven
    vanZyl](https://gist.github.com/rushsteve1/bc9ed33b850e17b42b2c78e9f18516d2)

## Syntax

``` {.rust}
fn main() {
    println!("Hello World!");
}
```

## Libraries

Rust libraries are hosted on <https://crates.io> and all \"crates\" can
be installed with [cargo](cargo).
