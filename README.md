# A-Frame Chess Board

## Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## About

This A-Frame Chess Board is a simple web-based 3D chessboard created using the A-Frame framework. It includes a textured chessboard, 3D chess pieces, a sky background, and even a video element.

## Prerequisites

Before you get started, make sure you have the following:

- A modern web browser that supports A-Frame (e.g., Chrome, Firefox, or Safari).
- A code editor for making modifications if needed.

## Getting Started

### Installation

To use this A-Frame Chess Board, simply open the `index.html` file in your web browser.

### Usage

- Use the mouse and keyboard to interact with the 3D scene:
  - **Mouse**: Click and drag to rotate the camera.
  - **W, A, S, D keys**: Move the camera forward, left, backward, and right, respectively.

- Enjoy the 3D chessboard, pieces, and background video!

## Customization

You can customize the A-Frame Chess Board in several ways:

- **Change 3D Models**: Replace the 3D models (GLTF and GLB) in the `3dmodels/` directory with your own models. Update the references in the HTML accordingly.

- **Adjust Camera Position**: Modify the initial camera position by changing the `position` attribute in the `<a-camera>` element.

- **Texture and Material**: Customize the textures and materials for the chessboard and other elements by changing the `material` attributes in the HTML.

- **Background**: Change the sky background by replacing the `src` attribute in the `<a-sky>` element with your preferred image.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/new-feature` or `git checkout -b bug/bug-fix`.
3. Make your changes and commit them with descriptive commit messages.
4. Create a pull request to the main repository's `master` branch.

## License

This project is licensed under the [MIT License](LICENSE.md).
