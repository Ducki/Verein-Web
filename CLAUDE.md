# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static website for "Sprötau Begeistert e.V." - a German community/cultural organization (Heimat- und Kulturverein). The
site is in German.

## Architecture

- **Pure static HTML** - No build system, bundler, or package manager

## Files

- `index.html` - Homepage with organization introduction
- `tanzveranstaltung.html` - Event page template (dance event example)
- `favicon.ico` - Site favicon

## Development

Open HTML files directly in a browser. No build or serve commands required.

## Styling Notes

- Uses CSS `light-dark()` function for automatic dark mode support
- Color scheme variables defined in `:root` (e.g., `--page-dark-bg`, `--text-light-color`)
- System font stack: `ui-sans-serif, system-ui, ...`
