# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## Unreleased



### Outras alterações


- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/Gifts-from-Friends-Compilation

- Standardize manifest files and update API requirements

Update all mod manifest files to follow a consistent structure with:
- Simplified, consistent mod names (removed descriptive subtitles)
- Updated MinimumApiVersion to 4.1.0 across all mods
- Standardized ContentPackFor with MinimumVersion 1.20.0 for MailFrameworkMod
- Removed deprecated Dependencies sections
- Simplified and refined Description fields
- Updated README with complete character names and version numbers
- Removed unnecessary presentes.txt file from Krobus mod

- Add Gifts from Friends mods for multiple NPCs

Add complete mod content packages for 11 NPCs (Emily, Lewis, Pam, Clint, Demetrius, George, Gus, Jas, Krobus, Vincent, and Willy). Each package includes mail.json configurations, i18n translations across 15+ languages, and manifest.json metadata. These mods provide progressive gift rewards based on friendship levels.

- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/Gifts-from-Friends-Compilation

- Add Mail Framework Mod content packs

Add three new Mail Framework Mod content packs providing progressive, friendship-based gifts and letters from Abigail, Alex, and Haley. Each pack includes 10 friendship levels with themed gifts, attachments, and localized messages in 15-16 languages.

- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/Gifts-from-Friends-Compilation

- Add 'Gifts from Elliott' and 'Gifts from Sam' mail packs

Introduce two Mail Framework content packs: Gifts from Elliott and Gifts from Sam. Adds manifests, mail.json definitions (IDs, attachments, friendship conditions, mail chains) and extensive i18n localization files (default plus cs,de,es,fr,hu,it,ja,ko,nl,pl,pt,ru,tr,uk,zh) for both packs to provide localized mail text and attachments.


### 📚 Documentação


- atualiza CHANGELOG.md [skip ci]

- atualiza CHANGELOG.md [skip ci]

- atualiza CHANGELOG.md [skip ci]

- atualiza CHANGELOG.md [skip ci]


## v1.5.0 - 2026-07-25



### Outras alterações


- Rename mod folders and add Shane gifts mod

Standardize mod folder naming from '[MFM] {Name} Gifts' to '[MFM] Gifts from {Name}'. Add new 'Gifts from Shane' mod with multilingual support. Update manifest versions to semantic versioning (1.0 → 1.0.0) and increase MinimumApiVersion for Pierre, Robin, and Wizard mods. Normalize line endings in JSON files. Add root manifest.json for compilation support.

- Add title for More Gifts From Friends Compilation

- Enhance changelog workflow with versioning and release

Updated workflow to read version from manifest and create a tag if the version changes. Added steps for generating release notes and creating a GitHub release with a zip package.

- Update commit sorting and parser configurations

Changed sort_commits from 'oldest' to 'newest' and updated commit_parsers to include a release group while removing style and build groups.

- Add files via upload

- Move changelog workflow to .github/workflows

Relocate changelog.yml to the standard .github/workflows directory where GitHub Actions workflows should be stored.

- Add GitHub Action to update CHANGELOG.md

- Add changelog configuration in cliff.toml

- V 1.0.0 do mod Gifts from Sandy adicionada

Todas as modificações e alterações foram salvas no repositório principal esta é somente uma copia para integrar a compilação.

- Initial commit


### 📚 Documentação


- atualiza CHANGELOG.md [skip ci]


