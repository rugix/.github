# The Open Lifecycle Layer for Embedded Linux

Rugix provides everything you need to build and maintain robust Linux-powered products, from development to production.

[Rugix Ctrl](https://github.com/rugix/rugix) provides **reliable lifecycle management for Linux devices**, with atomic system and application updates, automatic rollback, and flexible management of persistent state:

- **Fail-Safe System Updates**: Atomic A/B updates with automatic rollback on failure.
- **Application Lifecycle Management**: Atomic deployment and rollback of [application workloads](https://rugix.org/docs/ctrl/application-updates/).
- **State Management**: Flexible state management inspired by container-based architectures.
- **Efficient Delivery**: [Highly efficient delta updates](https://rugix.org/blog/efficient-delta-updates) minimizing bandwidth.
- **Secure Updates**: Cryptographic verification _before_ installing anything anywhere.
- **Compatibility Checks**: Verifies that system and application updates are compatible before installation.
- **Vendor-Agnostic**: Compatible with [various fleet management solutions](https://rugix.org/docs/ctrl/advanced/fleet-management) (avoids lock-in).
- **Flexible Boot Flows**: Supports [any bootloader and boot process](https://rugix.org/docs/ctrl/advanced/boot-flows).
- **Yocto Integration**: [Ready-made Yocto layers](https://github.com/rugix/meta-rugix) available.

Works with Yocto, Buildroot, and other Linux build systems.

[Rugix Admin](https://github.com/rugix/rugix-admin) complements Rugix Ctrl with a **lightweight, browser-based management interface for individual devices**. It lets developers and operators inspect system status, install updates, manage application workloads, and diagnose devices locally, making it ideal for development, demos, and field service.

In addition, [Rugix Bakery](https://github.com/rugix/rugix-bakery) lets you **build custom Linux distributions in days, not months**:

- **Supported Distributions**: Debian, Alpine Linux, and Raspberry Pi OS.
- **OTA Updates**: Over-the-air update capabilities powered by Rugix Ctrl out of the box.
- **Container-Based Builds**: Reproducible build environment from source to image.
- **System Variants**: Support for multiple configurations including test setups.
- **Integrated Testing**: Built-in system testing framework based on VMs.
- **SBOM Generation**: Built-in SBOM generation for regulatory compliance.

Use Rugix Bakery and Rugix Ctrl together for an end-to-end workflow from image creation through deployment and maintenance, or use Rugix Ctrl with your favorite build system.

**100% open-source and permissively licensed.** ❤️

Rugix is created and maintained by [Silitics](https://github.com/silitics), an independent, founder-owned company providing support and consulting for embedded Linux projects. Silitics also develops [Nexigon](https://github.com/nexigon), a fleet management solution.
