# antipasti

The antipode of paste(1), after an idea by Henrik Christian Grove.

## Usage

```
Usage: antipasti [OPTIONS] [FILES] ...
  Options are:
    -a, --append ........ open file(s) for appending (default 'w')
    -h, --help .......... this brief help text
    -v, --version ....... print version information
    -c, --copyright ..... show copying policy

Antipasti reads from stdin and writes to file1, file2, ..., fileN
such that lines 1, N+1, 2*N+1, ... are written to file1,
          lines 2, N+2, 2*N+2, ... are written to file2,
          et cetera.

Antipasti recognizes '-' and '+' as aliases for stdout resp. stderr.
```

## Requirements

* Python 3+

:smile:
