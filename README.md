# Cppmake

Cppmake is for Makefile generation

## Usage

```Bash
 cppmake -i <file> -c <compiler> -f <code filetype> -H <header filetype> -o <output name> <compiler arguments>
```

## Default parameters

- -c = g++
- -f = cpp
- -H = h
- -o = output

## Example

```Bash
cppmake -i main.cpp -c g++ -f cpp -H h -o main
```