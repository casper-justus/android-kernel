# Contributing

Thank you for your interest in contributing! Contributions are welcome in the form of bug reports, workflow improvements, new device support, and documentation fixes.

## Getting Started

1. **Fork** the repository and create a new branch from `main`:
   ```bash
   git checkout -b feat/your-feature-name
   ```
2. Make your changes.
3. Test the workflow by running it manually via the **Actions** tab on your fork.
4. Open a **Pull Request** against `main` with a clear description of what you changed and why.

## What You Can Contribute

- 📱 **New device support** — add defconfig mappings and AnyKernel3 device entries for other Samsung devices
- 🔧 **Workflow improvements** — faster build steps, better caching, toolchain upgrades
- 🐛 **Bug fixes** — patches for build failures, Kconfig issues, or packaging problems
- 📚 **Documentation** — clearer instructions, more device flash guides, translated READMEs

## Pull Request Guidelines

- Keep PRs focused — one change per PR
- Use clear, descriptive commit messages (e.g. `fix: correct Mali Kconfig sed pattern`)
- If adding a new device, include the device name, codename, and model number in the PR description
- Ensure the workflow still passes on your fork before submitting

## Reporting Issues

If a build fails, please open an issue and attach:
- The **compile log** artifact from the failed Actions run
- The kernel source URL and branch you used
- The KernelSU tag used
- Your device model

## Code of Conduct

Be respectful. This is an open project and everyone is welcome regardless of experience level.
