# catsay :cat:

catsay is a rewrite of [cowsay](https://en.wikipedia.org/wiki/Cowsay) written rust. This small project has been heavily inspired by [Practical Rust Projects](https://www.apress.com/gp/book/9781484255988).

## Installation :arrow_double_down:
`clone` the repo then run:
```bash
cargo build --release
```
## Usage :arrow_forward:
```bash
catsay 0.1.0

USAGE:
    catsay [FLAGS] [OPTIONS] [message]

FLAGS:
    -d, --dead       Makes the cat appear dead
    -h, --help       Prints help information
    -i, --stdin      Read the message from STDIN instead of the argument
    -V, --version    Prints version information

OPTIONS:
    -f, --file <catfile>    Load the cat picture from the specified file

ARGS:
    <message>    What doew the cat say? [default: Meow!]
```
