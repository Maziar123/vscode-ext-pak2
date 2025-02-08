# MZ Python Pack 2

![MZ Python Pack 2 Icon](mz-python-pak2.svg)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![VS Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/oss-mazi.mz-python-pak2)](https://marketplace.visualstudio.com/items?itemName=oss-mazi.mz-python-pak2)
[![VS Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/oss-mazi.mz-python-pak2)](https://marketplace.visualstudio.com/items?itemName=oss-mazi.mz-python-pak2)

## Overview

**MZ Python Pack 2** is an essential collection of Visual Studio Code extensions tailored for Python development. Whether you're a beginner or a seasoned developer, this extension pack enhances your productivity, streamlines your workflow, and provides powerful tools to write clean and efficient Python code.

## Features

- **Comprehensive Python Support:** From syntax highlighting to advanced debugging, get everything you need for Python development.
- **Enhanced Productivity:** Tools for code formatting, linting, and environment management streamline your coding process.
- **Integrated Jupyter Support:** Seamlessly work with Jupyter notebooks within VS Code.
- **Path Intellisense & File Utilities:** Navigate and manage your project files with ease.
- **Customizable Code Folding & Type Hinting:** Improve code readability and maintainability.

## Included Extensions

The extension pack includes these powerful tools:

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - Core Python support
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) - Type checking and code completion
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) - Jupyter notebook integration
- [Debugpy](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy) - Advanced debugging
- [isort](https://marketplace.visualstudio.com/items?itemName=ms-python.isort) - Import sorting
- [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter) - Code formatting
- [AutoPEP8](https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8) - PEP8 compliance
- [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent) - Smart indentation
- [MagicPython](https://marketplace.visualstudio.com/items?itemName=magicstack.MagicPython) - Syntax highlighting
- [Python Path](https://marketplace.visualstudio.com/items?itemName=mgesbert.python-path) - Path management
- [Python TypeHint](https://marketplace.visualstudio.com/items?itemName=njqdev.vscode-python-typehint) - Type hint support
- [Flake8](https://marketplace.visualstudio.com/items?itemName=ms-python.flake8) - Code linting
- [Python Environments](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-python-envs) - Environment management
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Path autocompletion
- [Dakara FoldPlus](https://marketplace.visualstudio.com/items?itemName=dakara.dakara-foldplus) - Code folding
- [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils) - File management
- [DoubleBot](https://marketplace.visualstudio.com/items?itemName=doublebot.doublebot) - Productivity tools

## Installation

### Via VS Code Marketplace

1. Open Extensions view (`Ctrl+Shift+X`)
2. Search for "MZ Python Pack 2"
3. Click Install

### Via Command Line

```bash
code --install-extension oss-mazi.mz-python-pak2
```

### Manual Installation

1. Clone repository:

```bash
git clone https://github.com/yourusername/mz-python-pak2.git
```

2. Open in VS Code:

```bash
cd mz-python-pak2 && code .
```

## Usage

After installation, extensions activate automatically when working with Python files. Key workflows:

- **Formatting:** Right-click -> Format Document (select Black or AutoPEP8)
- **Debugging:** Use `Run and Debug` sidebar
- **Jupyter Notebooks:** Open `.ipynb` files directly
- **Linting:** Errors appear in Problems panel (`Ctrl+Shift+M`)

![Code Formatting Example](screenshots/formatting.png)

## Configuration

Customize via VS Code settings (`Ctrl+,`):

```jsonc
{
  "python.linting.enabled": true,
  "python.formatting.provider": "black",
  "jupyter.askForKernelAtStartup": false
}
```

## Contributing

We welcome contributions! Follow these steps:

1. Fork the repository
2. Create feature branch:

```bash
git checkout -b feat/your-feature
```

3. Commit changes
4. Push to fork
5. Create PR on GitHub

## Changelog

### [1.0.0] - 2025-02-08

- Initial release
- Includes 17 essential Python extensions

## FAQ

**Q: How to update extensions?**<br/>
A: Individual extensions update automatically through VS Code.

**Q: Can I remove some extensions?**<br/>
A: Yes, you can disable any extensions after installation.

## License

MIT License - see [LICENSE](LICENSE) file

## Support

Open an issue on [GitHub](https://github.com/yourusername/mz-python-pak2/issues)

---

**MZ Python Pack 2** is proudly maintained by [oss mazi](mailto:contact@example.com)
