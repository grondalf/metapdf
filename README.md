# MetaPDF

An interactive bash script that makes the creation and editing of PDF bookmarks easier.

## Features

* Automatically detects your Linux distribution (Debian, Fedora, Arch, Alpine, etc.) and offers to install `pdftk` if missing.
* Automatically removes bloatware metadata lines that clutter the file.
* Opens your system's default text editor for easy modification and injects a ready-to-use template.
* Never overwrites the original file; creates a new `_fixed.pdf` version.

## Installation

1.  Save the script code into a file named `metapdf` under the `~/.local/bin/` directory.
2.  Make it executable by running on the terminal:
    ```bash
    chmod +x metapdf
    ```
3.  Reload you bash by running:
    ```bash
    source ~/.bashrc 
    ```

## Usage

Pass the PDF file you want to edit as an argument:
```bash
metapdf my_document.pdf
```

## Disclaimer

The script was made with AI assistance and for personal use. Please check the code before running it.
