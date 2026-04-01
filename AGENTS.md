> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use **Merchant** instead of "User" when referring to the business entity.
- Use **Member** for individuals within a merchant team.
- Use **Payment Link** to refer to checkout URLs.
- Use **Environment** (Live/Test) instead of "Mode".

## Style preferences

- **Language**: All documentation must be in **Spanish** unless otherwise specified.
- Use active voice and second person ("tú").
- Keep sentences concise — one idea per sentence.
- Use sentence case for headings.
- Bold for UI elements: Haz clic en **Configuración**.
- Code formatting for file names, commands, paths, and code references.

## Content boundaries

- Focus on external API consumers and merchant integrators.
- Do not document internal infrastructure or sensitive security protocols.
- Administrator-only features should be clearly marked with an "Admin" tag.
