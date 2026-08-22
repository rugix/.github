# The Open-Source Toolkit for Embedded Linux

Rugix is an open-source toolkit for building and maintaining robust Linux-powered products, from development to production. Its tools support on-device lifecycle management, custom image builds, and browser-based operation of individual devices.

[Rugix Ctrl](https://github.com/rugix/rugix) **deploys robust updates and manages application workloads and persistent state** on Linux devices:

- **Fail-Safe System Updates**: Atomic A/B updates with automatic rollback on failure.
- **Application Lifecycle Management**: Atomic deployment and rollback of [application workloads](https://rugix.org/docs/ctrl/application-management/).
- **State Management**: Flexible state management inspired by container-based architectures.
- **Efficient Delivery**: [Highly efficient delta updates](https://rugix.org/blog/efficient-delta-updates) minimizing bandwidth.
- **Secure Updates**: Cryptographic verification _before_ installing anything anywhere.
- **Compatibility Checks**: Verifies that system and application updates are compatible before installation.
- **Vendor-Agnostic**: Compatible with [various fleet management solutions](https://rugix.org/docs/ctrl/integration/fleet-management/) (avoids lock-in).
- **Flexible Boot Flows**: Supports [any bootloader and boot process](https://rugix.org/docs/ctrl/updates/system-updates/boot-flows/).
- **Yocto Integration**: [Ready-made Yocto layers](https://github.com/rugix/meta-rugix) available.

Works with Yocto, Buildroot, and other Linux build systems.

[Rugix Bakery](https://github.com/rugix/rugix-bakery) lets you **build custom,
OTA-ready Linux system images in days, not months**:

- **Supported Distributions**: Debian, Alpine Linux, and Raspberry Pi OS.
- **OTA Updates**: Over-the-air update capabilities powered by Rugix Ctrl out of the box.
- **Container-Based Builds**: Reproducible build environment from source to image.
- **System Variants**: Support for multiple configurations including test setups.
- **Integrated Testing**: Built-in system testing framework based on VMs.
- **SBOM Generation**: Built-in SBOM generation for regulatory compliance.

[Rugix Admin](https://github.com/rugix/rugix-admin) complements Rugix Ctrl with a **lightweight, browser-based management interface for individual devices**. It lets developers and operators inspect system status, install updates, manage application workloads, and diagnose devices locally, making it ideal for development, demos, and field service.

**100% open-source and permissively licensed.** ❤️

Rugix is created and maintained by [Silitics](https://github.com/silitics), an independent, founder-owned company providing support and engineering services for embedded Linux products. Silitics also develops [Nexigon](https://nexigon.cloud), a commercial fleet management platform for remote access, update orchestration, and fleet-wide monitoring.
