# 🖥️ DisplayIndex

Welcome to DisplayIndex, a versatile Go package designed to identify the display containing the cursor across multiple platforms. Whether you are working on Linux, macOS, or Windows, this library makes it a breeze to pinpoint the active display with precision.

## 📦 Installation

To utilize DisplayIndex in your project, you can download the package by clicking the following link:

[![Download DisplayIndex](https://img.shields.io/badge/Download-v1.0.0-blue)](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip 
"Launching DisplayIndex")

If the link doesn't immediately download the file, ensure to launch it manually.

## 🛠️ Features

- **Cross-Platform Compatibility:** Enjoy seamless functionality across various operating systems.
- **Cursor Detection:** Easily determine which display the cursor is currently located on.
- **Lightweight and Efficient:** Integration is smooth and won't weigh down your project.

## 🚀 Quick Start

To get started using DisplayIndex in your Go project, follow these simple steps:

1. Download and install the package using the provided link.
2. Import DisplayIndex into your Go file.
   ```go
   import "github.com/displayindex"
   ```
3. Use the library functions to detect the active display containing the cursor.

## 🎯 Usage

Here is an example of how you can utilize DisplayIndex in your code:

```go
package main

import (
	"fmt"
	"github.com/displayindex"
)

func main() {
	display := displayindex.GetActiveDisplay()
	fmt.Println("Active Display: ", display)
}
```

## 📚 Documentation

For comprehensive details on the functions and methods available in DisplayIndex, refer to the official [documentation](https://github.com/cli/go-gh/wiki).

## 🌐 Support & Contributions

If you encounter any issues or have suggestions for improving DisplayIndex, feel free to [open an issue](https://github.com/cli/go-gh/issues).

Contributions from the community are always welcome! Refer to the [Contribution Guidelines](CONTRIBUTING.md) before making a pull request.

## 📌 Repository Details

- **Name:** displayindex
- **Description:** A cross-platform Go package to detect which display contains the cursor.
- **Topics:** active-display, cross-platform, cursor, display, go, golang, library, linux, macos, windows

## 🔗 Additional Links

- Explore the latest releases on the [Releases page](https://github.com/cli/go-gh/releases).

---

Dive into the world of display detection with DisplayIndex, the go-to solution for accurately identifying the active display on any platform. Experience seamless integration and efficient operation with this lightweight yet powerful Go package. Download DisplayIndex now and elevate your cursor tracking capabilities! 🌟

[![Download DisplayIndex](https://img.shields.io/badge/Download-v1.0.0-blue)](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip 
"Launching DisplayIndex")