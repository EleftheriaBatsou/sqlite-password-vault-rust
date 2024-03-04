## Password vault in Rust with SQLite

This project is very similar to this "[password vault](https://github.com/EleftheriaBatsou/password-vault-rust)" only this time I've added a database (SQLite).
I've written an article about it [here](https://eleftheriabatsou.hashnode.dev/), so if you want to do something similar I'd highly recommend having a look.

#### Cargo.toml

Add the sqlite -> ```rusqlite = { version = "0.29.0", features = ["bundled"] }```

"Rusqlite is an ergonomic wrapper for using SQLite from Rust." - Crates.io

---

_P.S. This project is only for learning purposes_

_Credits: [Akhil Sharma](https://github.com/AkhilSharma90)_
