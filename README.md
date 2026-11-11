# rust-journey

[![CI](https://github.com/zairithm/rust-journey/actions/workflows/ci.yml/badge.svg)](https://github.com/zairithm/rust-journey/actions/workflows/ci.yml)

My Rust learning log. Each week is its own crate under `weeks/`, with tests, and a short note in `notes/`.

## What this project covers

- Ownership, borrowing and lifetimes
- Structs, enums, pattern matching and error handling
- Generics, traits, iterators and closures
- Writing tests for everything

## Getting started

```bash
cargo test --all
```

To add a week: copy `weeks/week-01` to `weeks/week-NN`, rename the package in its `Cargo.toml`, and add `notes/week-NN.md` from the template.

## Roadmap

Each open item is tracked as a [GitHub issue](https://github.com/zairithm/rust-journey/issues).

- [x] Week 1: setup and first programs
- [ ] Week 2: ownership and borrowing
- [ ] Week 3: structs, enums and match
- [ ] Week 4: collections and error handling
- [ ] Week 5: generics, traits and lifetimes
- [ ] Week 6: tests, iterators and closures
- [ ] Week 7: smart pointers

## License

MIT
