# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

A practice project for learning the GitHub PR workflow (fork/branch, commit, push, open a pull request) — not a production codebase.

## Commands

Run tests:
```bash
pytest
```

## Architecture

- `math_utils.py` — four standalone functions: `add`, `subtract`, `multiply`, `divide` (`divide` raises `ValueError` on division by zero).
- `test_math_utils.py` — pytest tests importing directly from `math_utils`, covering all four functions including `divide`'s zero-division error.
