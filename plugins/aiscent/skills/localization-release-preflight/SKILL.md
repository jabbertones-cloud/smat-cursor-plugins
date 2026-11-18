---
name: localization-release-preflight
description: Audit local Xcode String Catalogs, localized metadata and screenshots before a release.
---

# Local App Store localization preflight

1. Read actual Xcode targets, xcstrings catalogs and metadata exports. Report the locales present in files, never a preset locale count.
2. Preserve source-file context for ambiguous keys; distinguish purchase Order from sort order and other polysemous labels.
3. Check missing translations, interpolation placeholders, plurals, UI truncation candidates and locale-specific characters. Never invent runtime defects solely from extracted text.
4. Inspect supplied screenshot files for recorded pixel dimensions, target device family, locale and count. Do not claim uploads or generate screenshots.
5. Check any current Apple limits against primary Apple material; if not verified, mark the claim as unverified.
6. Return locale-by-locale findings with path, key, risk, suggested change and verification step.
7. This free skill never accesses App Store Connect, asks for an Apple private key or submits a release.
