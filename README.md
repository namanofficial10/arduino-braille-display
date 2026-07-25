# Arduino Braille Character TXT Archive

This repository preserves the original character-specific Arduino control programs created for a **single-cell refreshable Braille hardware prototype** developed during the **Smart India Hackathon 2022 Finals**.

## Repository Purpose

The files in this repository represent an early version of the Arduino logic used to generate individual Braille characters through a mechanically actuated prototype.

Each character was stored separately as a `.txt` file containing Arduino-compatible C/C++ logic.

Example:

```text
A.txt
B.txt
C.txt
...
Z.txt
```

These files are retained in their original format as a historical archive of the prototype implementation.

## Project Context

The broader SIH project focused on improving document accessibility for visually impaired users.

The complete solution included:

- PDF-to-EPUB document conversion
- Python-based text and character sequencing
- Arduino-based character control
- A single refreshable Braille cell
- Mechanical gears and actuators
- Custom 3D-printed parts

The Braille hardware displayed one character at a time.

For example:

```text
NAMAN
```

was rendered sequentially as:

```text
N → A → M → A → N
```

## Project Status

This repository is an archived historical component of the original prototype.

The code may require modification before use with current Arduino boards, libraries, operating systems or hardware configurations.

A newer C++ version of the character-control programs is maintained separately in:

https://github.com/namanofficial10/braille-characters-cpp

## Related Project

The complete SIH project overview and Python orchestration component are documented in:

https://github.com/namanofficial10/sih-braille-accessibility-system

## Important Note

This repository does not include:

- The Python orchestration layer
- PDF-to-EPUB conversion software
- 3D models
- Mechanical design files
- Complete hardware schematics

The prototype was created as part of a team effort and this repository represents only one preserved technical component.

## Author

**Naman Sharma**

- GitHub: https://github.com/namanofficial10
- Portfolio: https://namanofficial10.github.io/
