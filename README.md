# Wampoon Packages

A meta repository for centralizing package information used in the [Wampoon](https://github.com/orgs/wampoon-box/repositories) project.

## Overview

Wampoon is a Windows-based development stack that bundles Apache, MariaDB, PHP, and related tools. This repository serves as the central source of truth for package metadata, including versions, download URLs, and checksums.

## Package Manifest

The `packagesInfo.json` file contains an array of package definitions with the following structure:

| Field | Description |
|-------|-------------|
| `PackageID` | Unique identifier for the package |
| `Name` | Human-readable package name |
| `Version` | Package version (format: `major.minor.patch.build`) |
| `DownloadUrl` | Direct URL to download the package |
| `ArchiveFormat` | Optional. Archive type (defaults to `zip` if not specified) |

## Included Packages

| Package | Description |
|---------|-------------|
| **Apache HTTP Server** | Web server |
| **MariaDB Server** | Database server |
| **PHP Runtime** | PHP interpreter |
| **phpMyAdmin** | Web-based database management |
| **wampoon-dashboard** | Local development dashboard |
| **Wampoon Control Panel** | System tray control application |
| **Xdebug** | PHP debugging extension |
| **Composer** | PHP dependency manager |
| **Microsoft Visual C++ Runtime** | Required runtime libraries |

## Related Repositories

- [wampoon-box](https://github.com/orgs/wampoon-box/repositories) - All Wampoon project repositories

## License

This project is licensed under the [MIT License](LICENSE).
