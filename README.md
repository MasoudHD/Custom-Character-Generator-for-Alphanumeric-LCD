# ALCD Custom Character Generator

In case you live in a cave, or somewhere the internet occasionally disappears.

## What is this?

This spreadsheet helps you design custom 5x8 LCD characters and automatically converts them into C `uint8_t` arrays.

## How to use

1. Open the file in Excel.
2. Use the `Single` sheet to design one character.
3. Use the `Multi` sheet to design multiple characters at once.
4. Edit the character name.
5. Fill the 5x8 grid with OFF pixel color (Green) and ON pixel color (Black). Just copy the sample cell into character area.
6. Copy the generated output into your project.

## Output example

```c
const uint8_t CUSTOM_CHAR[8] = {0x00, 0x0E, 0x11, 0x04, 0x0A, 0x00, 0x04, 0x00};
```

