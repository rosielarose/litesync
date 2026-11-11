# LiteSync 0.19.0 - English UI build

Unofficial English-localized build of [KJoner/litesync](https://github.com/KJoner/litesync) 0.19.0.

Upstream has no i18n layer - every UI string is hardcoded Chinese. This build
patches those literals to English with an AST-based translator (Acorn),
preserving all template interpolations and property keys.

Install on iOS with [BRAT](https://github.com/tfthacker/obsidian42-brat):

- Repository: `rosielarose/litesync`
- Version: `0.19.0-en.1`

The plugin id is unchanged (`litesync`), so BRAT replaces the community plugin
in place rather than installing a second copy.

## License

Upstream is MIT - see `LICENSE`. Copyright (c) KJoner.
This build is unofficial and not affiliated with the upstream author.
