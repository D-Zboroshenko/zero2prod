Zero to production in Rust
-------------------------

This repository contains coding examples for exploring Rust capabilities in developing production services.

## How to build

Launch a (migrated) Postgres database via Docker:

```bash
./scripts/init_db.sh
```

Launch `cargo`:

```bash
cargo build
```


## How to test

Launch a (migrated) Postgres database via Docker:

```bash
./scripts/init_db.sh
```

Launch `cargo`:

```bash
cargo test 
```