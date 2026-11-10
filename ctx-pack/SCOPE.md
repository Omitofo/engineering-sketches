# ctx-pack

> **This project now lives in its own repository:**  
> → [https://github.com/Omitofo/ctx-pack](https://github.com/Omitofo/ctx-pack)

CLI tool that packages a folder into clean, structured context for LLMs.

## Core Goals
- Turn any project folder into high-quality context for AI tools
- Respect .gitignore and allow custom ignore rules
- Produce clean, readable output (Markdown or JSON)
- Provide useful metadata (token estimates, file tree, optional summaries)

## Possible Features (MVP → Nice-to-have)

### MVP
- Recursive directory walk
- .gitignore support
- Custom ignore patterns
- Clean file tree output
- Basic file content inclusion (with size limits)
- Markdown output

### Nice-to-have
- Token counting (approximate)
- Optional AI-generated file summaries
- JSON output mode
- Configurable depth / max file size
- Exclude binary files intelligently
- Support for multiple output formats

## Tech Direction (suggestion)
- TypeScript or Go (both excellent for CLIs)
- Commander.js / Cobra or similar for CLI parsing
- Clean separation of concerns (walker, filter, formatter, etc.)

## Definition of Done
- Installable via npm or as a binary
- Good `--help`
- Solid README with examples
- Basic tests
- Feels intentional and polished
