**English** | [Português](README.pt-BR.md)

# Record Management System in C

A terminal application in C that manages records stored directly in a binary file, built for my Algorithms 2 course. The focus is file handling, not databases: records are read from and written to disk with `fread`, `fwrite` and `fseek`.

## What it does

- create, list, update and search records (by ID or by name);
- logical deletion, marking a record as inactive without erasing its data;
- physical deletion, rewriting the file without that record;
- input validation for numbers and text, so invalid entries never reach the file;
- a help manual opened with F1, stored in a separate file obfuscated with a simple XOR cipher.

Records are modeled with structs and kept in a single binary file, with no external libraries.

## Tech stack

- C
- Standard library (stdio, stdlib, string, ctype)
- Binary file handling (fread, fwrite, fseek)
- Data modeling with structs

## How to run
```bash
gcc sistemaregistro.cpp -o record-system
./record-system
```

## Project structure
```text
c-record-management-system/
|-- sistemaregistro.cpp
`-- README.md
```

## Academic context

Built for my Algorithms 2 course, as an exercise in binary file handling, file pointers and data persistence without a database.

## Author

Developed by Daniel Augusto Silva.
