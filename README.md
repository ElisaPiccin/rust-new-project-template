# rust-new-project-template
A good starting point for a new Rust project

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)

## Notes (hello-marco)

**Namespace:** hello-marco (Cargo.toml)

[Tested with rustc 1.70.0, required to run "cargo update -p clap --precise 4.4.18"]

The Makefile contains some utilities:
```bash
make rust-version
```

```bash
make format
```

```bash
make lint
```

To rebuild execute this command:
```bash
cargo run -- --help
```

To test the application run something similar to: 
```bash
cargo run -- play --name "Marco"
```

Additional options:
```bash
./target/debug/hello-marco --help
```

