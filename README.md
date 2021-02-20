# README

The hello cargo example from https://doc.rust-lang.org/book/ch01-03-hello-cargo.html

```shell
# create a new cargo project
cargo new hello_cargo

# change into the newly created project directory
cd hello_cargo

# build the project
# creates the project executable file within the ./target/debug folder
cargo build

# run the project
cargo run

# check the project compiles
# faster alternative to rebuilding each time
cargo check

# create an optimised release build
# benchmark against this version of the project
cargo build --release
```
