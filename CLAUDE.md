# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Running

```bash
python3 hello.py
```

## Tests

```bash
python3 -m unittest test_hello -v
```

## Architecture

Single-file Python script. `main()` contains the program logic and is called via the `if __name__ == "__main__"` guard.
