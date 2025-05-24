# Kilo Text Editor (Tutorial Implementation)

This project is a personal implementation of the [Kilo Text Editor](https://viewsourcecode.org/snaptoken/kilo/index.html) tutorial by antirez (Salvatore Sanfilippo). It is a lightweight, command-line text editor written in C, designed to teach the basics of building a terminal-based application from scratch.

## Features

- Syntax highlighting for a few languages
- Basic text editing (insert, delete, save, open)
- Scrollable, responsive interface
- Minimal dependencies

## Getting Started

### Prerequisites

- GCC (or any C compiler)
- Linux or macOS terminal (should work in most POSIX environments)

### Building

Clone this repository and compile using:

```sh
gcc -o kilo kilo.c -std=c99 -Wall
```

(This assumes your main file is named `kilo.c`.)

### Running

Start the editor with:

```sh
./kilo
```

You can open a file by passing its name:

```sh
./kilo filename.txt
```

## Usage

- Arrow keys to move cursor
- Ctrl-S to save
- Ctrl-Q to quit
- Ctrl-F to search

(See the tutorial for more details.)

## Credits

- Based on [viewsourcecode.org/snaptoken/kilo](https://viewsourcecode.org/snaptoken/kilo/index.html) by Salvatore Sanfilippo (antirez).
- This implementation follows along with the tutorial and is for educational purposes.

## License

See the [tutorial’s original license](https://github.com/antirez/kilo/blob/master/LICENSE) for reference.
