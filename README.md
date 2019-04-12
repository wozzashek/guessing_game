# Rust Guessing Game

This is all part of the Rust learning book, documentation updated as we go along

## main

Using the I/O library

Created a mutable variable 'guess' of Type string

Used I/O library to allow user input into variable 'guess'

Caught an error using .expect

Then used placeholders in prinln1! to print users input

## Crates
Added in the toml file, under [dependencies]

cargo build will bring in compile and add relevant crate data to 'Cargo.lock' file

Can use 'cargo update' to update packages

We used the rand crate, and use a thread to generate a random number everytime the program is run


## Convert entry to int32

```rust
let guess: u32 = guess.trm().parse()
    .expect("Please type a number");
```

## Added loop & error handling

```rust
loop {}
```
Added error handling

## Removed display of random number