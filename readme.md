
# Dibujo

Dibujo is a drawing application with features like free drawing, rectangles, circles, and text input (can't change the size of the text yet). It also includes a color picker and supports background color changes.

## Features

- Freehand drawing with adjustable brush thickness.
- Draw rectangles, circles, and add text with preview options.
- A built-in color picker for brush colors.
- Background color cycling with a button or key shortcut (`B`).

## Installation

### Using Homebrew
```bash
brew tap soycarlo99/dibujo-tap
brew install dibujo
```

### Build From Source
Clone the repository and build the program manually:
```bash
git clone https://github.com/soycarlo99/dibujo.git
cd dibujo
make
./dibujov0.1
```

## Usage

- Run the program with:
  ```bash
  dibujov0.1
  ```
- Use the buttons or keyboard shortcuts to switch modes:
  - **Free Draw**: Shortcut: Default mode
  - **Rectangle**: Button or `R`
  - **Circle**: Button or `C`
  - **Text**: Button or `T`

## Dependencies

- [SFML 2](https://www.sfml-dev.org/)

## Contributing

Contributions are welcome! Open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.