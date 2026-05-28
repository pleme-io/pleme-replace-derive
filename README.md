# pleme-replace-derive

Per-field swap: pub fn replace_<field>(&mut self, v: <Type>) -> <Type>. Sets the new value, returns the old one (via std::mem::replace).

[![Build](https://github.com/pleme-io/pleme-replace-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-replace-derive.svg)](https://crates.io/crates/pleme-replace-derive)

## Install

```toml
[dependencies]
pleme-replace-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
