# CTS LMDDI Software

CTS LMDDI is an open-source stack, composed primarily of Linux kernel driver software, designed for niche, legacy, and poorly supported device. LMDDI consists of a collection of drivers, patches, and development tools, written in C and Rust, that enable these devices to perform reliably and efficiently on modern Linux systems.

With LMDDI, you can customize or receive driver support for virtually any hardware. The initiative provides a free, open-source, integrated, and maintainable software ecosystem for the development, testing, collaboration, and deployment of drivers and device-support tools. LMDDI is especially well-suited for embedded Linux systems, legacy or poorly supported hardware, and devices without official or ongoing driver support.

LMDDI is powered by CTS's  [Device Driver Interface for Portability (DDIP)](https://github.com/Charged-Technology-Solutions/DDIP) an open-source software written in C and Rust. DDIP enables developers to create portable, modular drivers that support a wide range of devices, from common consumer hard to legacy, rare, and undocumented enterprise variants. By abstracting hardware specifics into a unified API, DDIP allows LMDDI drivers to maintain high performance, stability, and maintainability across Linux kernel versions.

LMDDI™ supports Linux kernel programming and includes all necessary drivers, patches, and utilities to ensure reliable operation. It contributes improvements to in-tree kernel drivers, providing enhanced performance, quality, and stability while maintaining compatibility with ongoing Linux kernel development. Core driver functionality is separated from device-specific modules, allowing seamless support for legacy, rare, and undocumented Realtek variants without destabilizing the kernel. Each module implements standardized interfaces for device operations, enabling portable and maintainable driver code across multiple kernel versions. LMDDI™ also incorporates an automated benchmarking and profiling system, allowing developers to measure throughput, latency, and stability on any supported device and automatically generate optimized module parameters for improved performance and reliability.

> [!IMPORTANT]
> Kernel development and testing for LMDDI is performed on the latest Gentoo release `gentoo-sources` kernel, ensuring compatibility with modern kernel features and long-term maintainability.

## Getting and Building LMDDI-E™ from Source

Please refer to this repository for instructions on compiling and installing RMDDI-E™ drivers on supported Linux distributions.

## RMDDI-E™ Documentation

This repository contains source code, patches, and documentation including changelogs and development notes. The `/docs` folder has all current documentation. The `develop` branch contains the latest updates and upcoming improvements.

The LMDDI documentation homepage is [www.docs.lmddi.org](https://www.docs.lmddi.org).

For information on how to contribute to the LMDDI, see [Contributing to LMDDI-E™](https://www.lmddi.org/contribute).

## Older LMDDI Releases

For release information for older LMDDI versions, refer to the `/releases` folder of this repository.
