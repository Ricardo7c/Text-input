# Text input library
A simple library for interactive text input in the terminal. It displays a message to the user and captures input synchronously, returning the entered text as a String (with spaces and line breaks removed). Ideal for CLI applications in Rust that need direct and clean user input.

Example:

```rust
use text_input::text;

fn main() {
    let name = text("What's your name? ");
    print!("Hi, {}", name);
}
```

```shell
$ cargo run

What's your name? Rust
Hi, Rust
