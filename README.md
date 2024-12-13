Simple script to convert an SMD resistor code to the resistance it represents.

Currently supports 3-digit EIA, 4-digit EIA, and EIA 96 codes.

## Usage

Example:
```
❯ resistor 01C
10 kΩ
```

For convenience, you can pass multiple codes:
```
❯ resistor 01C 622
10 kΩ
6.2 kΩ
```

## Installation

It's just a single-file Python script. Add it to your path however you want (copy to a folder, symlink, whatever).
