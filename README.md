[![Actions Status](https://github.com/onlydisco/hexlet-gendiff/workflows/hexlet-check/badge.svg)](https://github.com/onlydisco/hexlet-gendiff/actions)
[![validate](https://github.com/onlydisco/hexlet-gendiff/actions/workflows/validate.yml/badge.svg)](https://github.com/onlydisco/hexlet-gendiff/actions/workflows/validate.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/36be9d23cbbeade1906f/maintainability)](https://codeclimate.com/github/onlydisco/hexlet-gendiff/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/36be9d23cbbeade1906f/test_coverage)](https://codeclimate.com/github/onlydisco/hexlet-gendiff/test_coverage)

# GenDiff

### Description:
A CLI application. Compares two configuration files and shows a difference in three different output formats: stylish, plain and json. Supports flat and nested structures, accepts JSON and YAML files.

### Installation:

    make install

### Usage:

    gendiff [options] <filepath1> <filepath2>

    Arguments:
      filepath1            Path to file #1
      filepath2            Path to file #2

    Options:
      -V, --version        output the version number
      -f, --format <type>  output format (default: "stylish")
      -h, --help           display help for command

### Asciinema gendiff for two files in stylish-format:
[![asciicast](https://asciinema.org/a/542889.svg)](https://asciinema.org/a/542889)

### Asciinema gendiff for two files in plain-format:
[![asciicast](https://asciinema.org/a/542890.svg)](https://asciinema.org/a/542890)

### Asciinema gendiff for two files in json-format:
[![asciicast](https://asciinema.org/a/542891.svg)](https://asciinema.org/a/542891)
