# 🧹 RAM Cleaner - Windows Batch Script

A lightweight Windows batch script that cleans temporary files, cache, and system junk to free up RAM and disk space — instantly with a single double-click.

![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)
![Language](https://img.shields.io/badge/language-Batch-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)
![Admin](https://img.shields.io/badge/requires-Administrator-red.svg)

---

## ⚡ What It Does

The script performs a comprehensive cleanup of temporary and cached files across multiple Windows directories to reclaim system resources.

### 🗑️ Cleanup Targets

| Target | Path | Description |
|---|---|---|
| Windows Temp | `C:\Windows\Temp\` | System-level temporary files |
| Prefetch Cache | `C:\Windows\Prefetch\` | Application prefetch data |
| User Temp | `%temp%\` | Current user's temporary files |
| Temporary Internet Files | `C:\Windows\tempor~1\` | Legacy cached internet files |
| Windows Temp (alt) | `C:\Windows\tmp\` | Alternate temp directory |
| Temp Flash Files | `C:\Windows\ff*.tmp` | Leftover Flash temporary files |
| Browser History | `C:\Windows\history\` | Legacy browser history |
| Cookies | `C:\Windows\cookies\` | Legacy stored cookies |
| Recent Files List | `C:\Windows\recent\` | Recent documents history |
| Print Spooler | `C:\Windows\Spool\Printers\` | Stuck print jobs |
| Swap File | `C:\WIN386.SWP` | Legacy Windows swap file |

---

## 🚀 Getting Started

### Prerequisites

- **Windows OS** (7 / 8 / 10 / 11)
- **Administrator privileges** (required to access system directories)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ram-cleaner.git
