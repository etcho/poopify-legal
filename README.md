# poopify-legal

Public legal documents of the Poopify app, published with GitHub Pages at https://etcho.github.io/poopify-legal/.

| Page | Source |
|---|---|
| https://etcho.github.io/poopify-legal/privacy-policy/ | `privacy-policy/index.md` (Section 12 comes from `_includes/consumer-health-data.md`) |
| https://etcho.github.io/poopify-legal/terms-of-use/ | `terms-of-use/index.md` |
| https://etcho.github.io/poopify-legal/delete-account/ | `delete-account/index.md` (the account deletion link required by Google Play) |
| https://etcho.github.io/poopify-legal/consumer-health-data/ | `consumer-health-data/index.md` (same text as Section 12, as a separate page) |

English is the source language. The translations are written and kept in this repository only; the legal texts are **not** sent to Crowdin (no outside contributions to legal texts).

## Translations

Each app language has its own folder named with the Crowdin language code (`pt-BR/`, `es-ES/`, `fr/`, `it/`, `de/`, `nl/`, `pl/`, `cs/`, `sv-SE/`, `ru/`, `uk/`, `he/`, `hi/`, `ja/`, `ko/`, `zh-CN/`, `zh-TW/`) with the same four pages, published at `/<lang>/privacy-policy/` and so on. Section 12 of each translated privacy policy comes from `_includes/<lang>/consumer-health-data.md`.

- Every translated page starts with a notice that the English version prevails, linking to it.
- Menu names and buttons quoted in the texts must match the app's strings in that language (`www/lang/<lang>.js` in the app repository).
- Links inside a translation point to the pages in the same language. Archived versions (`/1.0/`) exist only in English, so links to previous versions point to the English archive.
- Hebrew pages wrap the content in `<div dir="rtl" markdown="1">`.
- The current English pages start with `{% include languages.md page="..." %}`, a bar linking to the same document in every language, and the home page (`index.md`) has a table with every language. When adding a language, add it to both.
- When a new English version is published, update every translation (Version, Effective date, Version history) in the same commit, so a language never shows an outdated text as current.

## Publishing a new version

Every published version has its own permanent page (`privacy-policy/1.0/`, `terms-of-use/1.0/`...) next to the current one (`privacy-policy/`, `terms-of-use/`). The app records which version each user accepted, so **a version folder is never edited after it is published**.

1. Edit the current page (`privacy-policy/index.md` or `terms-of-use/index.md`): update **Version** and **Effective date** at the top and add a line to **Version history**.
2. Copy it to a new folder for that version (`privacy-policy/1.1/index.md`) with `permalink: /privacy-policy/1.1/`. For the privacy policy, replace `{% include consumer-health-data.md %}` in the copy with the text of the include, so the copy never changes. If Section 12 changed, edit `_includes/consumer-health-data.md` too.
3. Version numbers are `major.minor`:
   - **minor** (1.0 → 1.1): wording, clarifications, nothing that changes what data is processed or why. The app asks nothing from the user.
   - **major** (1.x → 2.0): material changes. Update `CloudSync.CONSENT` in the app: users who sync see the consent screen again and sync pauses until they accept.
4. Update every translation in this repository in the same commit (see Translations above).
