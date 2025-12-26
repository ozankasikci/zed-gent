# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Zed editor extension for Gent syntax highlighting. Uses tree-sitter-gent as a submodule.

## Key Files

- `extension.toml` - Zed extension manifest
- `languages/gent/config.toml` - Language settings (.gnt extension, comments, brackets)
- `languages/gent/highlights.scm` - Syntax highlighting queries
- `grammars/gent/` - tree-sitter-gent submodule

## Related Projects

- **gent-programming-language** (`/Users/ozan/Projects/gent-programming-language`) - Main Gent interpreter
- **tree-sitter-gent** (`/Users/ozan/Projects/tree-sitter-gent`) - Tree-sitter grammar

When adding new syntax, update: `highlights.scm` (this repo) + `grammar.js` (tree-sitter) + `grammar.pest` (gent).
