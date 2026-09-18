# Changelog

All notable changes to alacritty_terminal are documented in this file. The
sections should follow the order `Added`, `Changed`, `Deprecated`, `Fixed` and
`Removed`.

**Breaking changes are written in bold style.**

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## 0.26.1-dev

### Fixed

- Panic when the PTY could not be set to non-blocking
- Off-by-one in ViMotion::ParagraphUp
- Unbounded per-cell memory usage for zero-width cells
- Unsoundness in `Row::new` when `columns == 0`

