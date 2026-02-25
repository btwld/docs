> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the documentation site for [Mix](https://github.com/btwld/mix), a styling system for Flutter
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "Styler" not "style builder" (e.g., `BoxStyler`, `TextStyler`)
- Use "variant" for conditional style application (hover, dark mode, etc.)
- Use "token" for design token references (`ColorToken`, `SpaceToken`, etc.)
- Use "MixScope" not "MixTheme" (v2.0 terminology)
- Use "directive" for value transformations (text/number directives)
- Use "modifier" for widget wrapping effects (opacity, transform, etc.)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- All code examples use Dart

## Content boundaries

- Document Mix v2.0 API (Styler-based)
- Include migration guides from v1.x
- Do not document internal implementation details
- Do not document deprecated v1.x API as primary reference
