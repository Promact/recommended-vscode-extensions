# Recommended VSCode Extensions for Development

## Overview

This repository contains recommended VSCode extensions for different programming languages and frameworks. The structure is organized into four parent folders, each corresponding to a specific language or framework. Except for the JavaScript folder, all other folders contain a `.vscode` subfolder.

The idea is simple: clone this repository and copy the `.vscode` folder from the language or framework folder you are interested in, and paste it into your project's root directory. This will set up your VSCode environment with extensions that are tailored for that specific language or framework.

## Table of Contents

- [Recommended VSCode Extensions for Development](#recommended-vscode-extensions-for-development)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Folder Structure](#folder-structure)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/Promact/recommended-vscode-extensions.git
    ```

2. Navigate to the cloned directory.

    ```bash
    cd recommended-vscode-extensions
    ```

## Usage

1. Navigate to the folder corresponding to the language or framework you are working with.
2. Copy the `.vscode` folder.
3. Paste the `.vscode` folder into the root directory of your project.

For example, if you are working on a Python project:

```bash
cp -r Python/.vscode /path/to/your/python/project/
```

## Folder Structure

```
.
├── JavaScript
│   ├── React
│   │   └── .vscode
│   └── Angular
│       └── .vscode
├── Python
│   └── .vscode
├── Java
│   └── .vscode
└── Dotnet
    └── .vscode
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin new-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License.

---

Happy Coding! 🚀
