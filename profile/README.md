# Open Lifecycle Layer for Embedded Linux Products

Rugix provides everything you need to build and maintain robust Linux-powered products, from development to production.

[Rugix Ctrl](https://github.com/rugix/rugix) lets you **deploy updates with confidence, never bricking a device**:

- **A/B Updates**: Atomic system updates with automatic rollback on failure.
- **Delta Updates**: [Highly-efficient delta updates](https://rugix.org/blog/efficient-delta-updates) minimizing bandwidth.
- **Signature Verification**: Cryptographic verification _before_ installing anything anywhere.
- **State Management**: Flexible state management inspired by container-based architectures.
- **Application Updates**: Atomic deployment and rollback of [application workloads](https://rugix.org/docs/ctrl/application-updates/).
- **Vendor-Agnostic**: Compatible with [various fleet management solutions](https://rugix.org/docs/ctrl/advanced/fleet-management) (avoids lock-in).
- **Flexible Boot Flows**: Supports [any bootloader and boot process](https://rugix.org/docs/ctrl/advanced/boot-flows).
- **Yocto Integration**: [Ready-made Yocto layers](https://github.com/rugix/meta-rugix) available.

Works with Yocto, Buildroot, and other Linux build systems.

In addition, [Rugix Bakery](https://github.com/rugix/rugix-bakery) lets you **build custom Linux distributions in days, not months**:

- **Supported Distributions**: Debian, Alpine Linux, and Raspberry Pi OS.
- **OTA Updates**: Over-the-air update capabilities powered by Rugix Ctrl out of the box.
- **Container-Based Builds**: Reproducible build environment from source to image.
- **System Variants**: Support for multiple configurations including test setups.
- **Integrated Testing**: Built-in system testing framework based on VMs.
- **SBOM Generation**: Built-in SBOM generation for regulatory compliance.

Use both together for a complete solution, or use Rugix Ctrl with your favorite build system.

**100% open-source and permissively licensed.** ❤️

Rugix has been created and is maintained by [Silitics](https://github.com/silitics), a company offering support and consulting for embedded Linux projects, as well as [Nexigon](https://github.com/nexigon), a fleet management solution. Silitics is 100% privately owned and led by its founder [@koehlma](https://github.com/koehlma).
