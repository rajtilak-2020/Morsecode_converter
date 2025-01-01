# Morse Code Converter

This project converts user-input words into Morse code. Each letter or digit in the input is translated into its corresponding Morse code representation using a predefined dictionary.

## Features
- Converts English letters (a-z) and digits (0-9) into Morse code.
- Supports continuous input from the user.

## How It Works
1. The user inputs a word or phrase.
2. Each character of the input is checked against a predefined dictionary of Morse code symbols.
3. The corresponding Morse code is appended to the output string.
4. The Morse code output is displayed to the user.

## Usage
1. Clone or download the repository.
2. Run the script in a Python environment:
   ```bash
   python morse_code_converter.py
   ```
3. Input a word or phrase when prompted.
4. The script will output the Morse code equivalent.

## Example
### Input
```
type: hello
```

### Output
```
.... . .-.. .-.. ---
```

## Morse Code Reference
The following table outlines the Morse code symbols used in this project:

| Character | Morse Code |   | Character | Morse Code |
|-----------|------------|---|-----------|------------|
| a         | .-         |   | n         | -.         |
| b         | -...       |   | o         | ---        |
| c         | -.-.       |   | p         | .--.       |
| d         | -..        |   | q         | --.-       |
| e         | .          |   | r         | .-.        |
| f         | ..-.       |   | s         | ...        |
| g         | --.        |   | t         | -          |
| h         | ....       |   | u         | ..-        |
| i         | ..         |   | v         | ...-       |
| j         | .---       |   | w         | .--        |
| k         | -.-        |   | x         | -..-       |
| l         | .-..       |   | y         | -.--       |
| m         | --         |   | z         | --..       |
| 1         | .----      |   | 6         | -....      |
| 2         | ..---      |   | 7         | --...      |
| 3         | ...--      |   | 8         | ---..      |
| 4         | ....-      |   | 9         | ----.      |
| 5         | .....      |   | 0         | -----      |

## Project Structure
- `morse_code_converter.py`: Main script containing the Morse code dictionary and the logic for conversion.

## Future Enhancements
- Add support for punctuation.
- Handle spaces between words in the input.
- Provide a graphical user interface (GUI) for easier use.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- Inspired by the simplicity of Morse code as a communication method.
- Morse code references taken from publicly available sources.
