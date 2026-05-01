# Changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](https://semver.org/).

## [1.0.0] - 2026-05-01
### Added
- GitHub Actions CI workflow for building KernelSU-patched kernel for Samsung Galaxy A04s (SM-A047F)
- Clang 17 toolchain setup from ZyCromerZ/Clang
- KernelSU integration via official setup script with configurable tag
- Auto-patch for Mali GPU Kconfig `shell()` syntax errors
- Kernel configuration with KernelSU, kprobes, and overlay FS enabled
- AnyKernel3 packaging producing a flashable ZIP
- DTB collection and inclusion in flash package
- Optional GitHub Release creation with build metadata
- Compile log artifact upload on build failure
- 12GB swap space setup for large kernel builds
- MIT License
- CONTRIBUTING.md guide
