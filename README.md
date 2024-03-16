# processtree-rust

Finally an initial working version of the processtree example implemented in Rust.

## Building and running

```
$ cargo build --release
$ ./target/release/fakeps 1000000 > 1000000.txt
$ export RUST_LOG=info
$ ./target/release/processtree < 1000000.txt > /dev/null
```

## References

- https://doc.rust-lang.org/cargo/guide/project-layout.html
- https://github.com/proptest-rs/proptest
- https://github.com/rust-unofficial/awesome-rust?tab=readme-ov-file