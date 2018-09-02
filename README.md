# antipasti

The antipode of paste(1), after an idea by Henrik Christian Grove.

## Usage

```
Usage: antipasti [OPTIONS] FILE [FILE …]

positional arguments:
  FILE             filename

optional arguments:
  -h, --help       show this help message and exit
  -v, --version    show version information and exit
  -c, --copyright  show copying policy and exit
or:
  -a, --append     append to the given FILEs, do not overwrite

This program reads from standard input and writes to file1..fileN
such that lines 1, N+1, 2N+1, … are written to file1,
          lines 2, N+2, 2N+2, … are written to file2,
          et cetera.

Minus (‘-’) and plus (‘+’) are recognized as aliases for standard
input and standard error, respectively.
```

## Requirements

* Python 3.5+
  * This program was rewritten as an excercise in type annotations

## License

GNU General Public License v3+

:smile:
