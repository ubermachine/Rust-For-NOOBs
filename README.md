Rust-Programming-Language

Deep dive into rust lang which i thought will be fun to learn instead of C++ SOURCE-https://www.rust-lang.org/learn
Day 1-INSTANT regret!!!

Install Rust to unix based OS

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs |sh

Path variable will be automatically set up upon restart till then you can use it in terminal using

source $HOME/.cargo/env

Next step will obviously be to configure VS code to use it by heading too Vs code marketPlace off the bat we will start using cargo CARGO-Cargo is Rust’s build system and package manager. Lets set up our workspace

cargo new hello_cargo
$ cd hello_cargo

And inside there will be a src folder with main.rs and blindly type cargo run in the terminal of vscode we will now see the beautiful beautiful Hello, world! printed now who does not love to see it.

then lets head to https://doc.rust-lang.org/stable/rust-by-example where you will start scratching your head if you have forgotten your old friend C.