# hexydump
Colorful hex dump

This is a simple hexdump-like utility. It changes the color of the byte based on the ASCII value. This was mostly for fun but could also come in handy in some situations I guess maybe.

## Usage
```
USAGE:
    hexydump [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -f, --hexdump <hexdump>    file to dump hexily
```

## Examples

Pass a file to hexydump:
```
./hexydump -f <filename>
```

Pipe input to hexydump:
```
cat <filename> | ./hexydump
```

