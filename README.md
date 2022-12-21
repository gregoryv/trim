trim - Convenient line trimmer with sane defaults

![](./trim_logo.svg)

## Quick start

    $ go install github.com/gregoryv/cmd/trim@latest
    $ trim -h
    Usage: trim [OPTIONS]
    
    Options
        -c, --columns : 72
        -s, --suffix : "..."
        -t, --tab-width : 4
            number of spaces
    
        -h, --help


trim trims lines on stdin, e.g.

    $ cat testdata/example.txt | trim


## Features

1. Trim by specific column
1. Indicate trim with suffix
1. Replace tabs with spaces
1. Replace $HOME/path with ~/path
