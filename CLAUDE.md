# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Kannada language learning resource repository. Kannada is a Dravidian language spoken by ~50 million people. The project is defunct; the active repository is at https://github.com/chirs/languages.

## Structure

- **letters.py** — Python dictionaries mapping Kannada Unicode characters to romanized equivalents. Contains three mappings: `vowels`, `numerals`, and `consonants` (organized by articulation: velars, palatals, retroflex, dentals, labials).
- **dialogues** — Plain text file with sample English-language dialogues for language learning practice.

## Notes

- No build system, tests, or dependencies. This is a data-only reference project.
- Kannada script uses Unicode block U+0C80–U+0CFF. The romanization in letters.py follows IAST conventions where applicable.
