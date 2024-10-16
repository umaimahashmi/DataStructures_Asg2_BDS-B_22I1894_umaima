# Simple Text Editor

This project implements a simple text editor in C++ using a linked list structure to manage the text. The editor supports basic text operations such as inserting characters, navigating through the text, saving to a file, and loading from a file. Additionally, it includes a simple spell-checking feature with suggestions for correcting misspelled words.

## Features

- **Text Insertion**: Add characters to the text.
- **Navigation**: Move the cursor left, right, up, and down.
- **File Operations**: Save the text to a file and load text from a file.
- **Spell Checking**: Identify and display misspelled words.
- **Correction Suggestions**: Provide suggestions for correcting misspelled words by omitting or swapping letters.

## Files

- `notepad.cpp`: The main implementation of the text editor.
- `dictionary.txt`: A dictionary file used for spell checking.
- `README.md`: This file, providing an overview of the project.

## Usage

1. Compile the `notepad.cpp` file.
2. Run the executable.
3. Use the keyboard to interact with the text editor:
   - Enter characters to insert them into the text.
   - Use arrow keys to navigate.
   - Press `Ctrl+S` or `S` to save the text to `save.txt`.
   - Press `Ctrl+L` or `L` to load text from `save.txt`.
   - Press `Esc` or `q` to quit the editor.
