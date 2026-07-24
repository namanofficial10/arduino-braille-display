# Single-Cell Refreshable Braille Prototype

This repository preserves the Arduino control programs created for a **single-cell refreshable Braille hardware prototype** developed as part of a solution presented at the **Smart India Hackathon 2022 Finals**.

## Project Context

The primary SIH problem statement focused on creating software to convert PDF documents into an accessible EPUB format for visually impaired users.

Alongside the software solution, our team also developed a hardware prototype that could display Braille characters sequentially using:

- Arduino-based control
- C/C++ character programs
- Python-based sequencing
- Mechanical gears and actuators
- Custom 3D-printed components
- A single refreshable Braille cell

## How the Prototype Worked

The hardware contained one Braille cell capable of displaying one character at a time.

For example, to display the word:

```text
NAMAN
```

The system sequentially displayed:

```text
N → A → M → A → N
```

The workflow was:

```text
Input text
    ↓
Python character sequencing
    ↓
Character-specific Arduino program
    ↓
Mechanical actuation
    ↓
Braille character displayed
    ↓
Next character
```

## Repository Contents

The repository currently contains character-specific `.txt` files for letters of the English alphabet.

Each file preserves the Arduino C/C++ control logic used to generate the corresponding Braille character on the prototype.

Example:

```text
A.txt
B.txt
C.txt
...
Z.txt
```

The files remain in their original format to preserve the historical implementation of the prototype.

## Technology Used

- Arduino
- Embedded C/C++
- Python
- Serial communication
- Mechanical prototyping
- 3D printing
- Assistive technology design

## Project Status

This is an archived educational prototype from 2022.

The repository is maintained primarily for:

- Portfolio documentation
- Historical reference
- Demonstrating hardware-software integration
- Showcasing assistive technology experimentation

The code may require modification before being used with modern Arduino boards, libraries, operating systems or hardware configurations.

## Important Note

This repository contains only the character-control programs preserved from the original prototype. The complete PDF-to-EPUB software, Python orchestration layer, hardware design files and 3D models are not currently included.

This prototype was created as part of a team effort. The repository represents the Arduino character-control component associated with the project and does not imply individual ownership of every software, mechanical or hardware component.

## Responsible Use

This project is intended for educational, research and assistive-technology experimentation.

It should not be treated as a production-ready refreshable Braille display or a certified accessibility device.

## Author

**Naman Sharma**

- GitHub: https://github.com/namanofficial10
- Portfolio: https://namanofficial10.github.io/

## Acknowledgement

Developed as part of a team solution presented at the **Smart India Hackathon 2022 Finals**.
