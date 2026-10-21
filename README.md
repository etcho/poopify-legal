# poopify-legal

Public legal documents of the Poopify app, published with GitHub Pages at https://etcho.github.io/poopify-legal/.

| Page | Source |
|---|---|
| https://etcho.github.io/poopify-legal/privacy-policy/ | `privacy-policy/index.md` (Section 12 comes from `_includes/consumer-health-data.md`) |
| https://etcho.github.io/poopify-legal/terms-of-use/ | `terms-of-use/index.md` |
| https://etcho.github.io/poopify-legal/delete-account/ | `delete-account/index.md` (the account deletion link required by Google Play) |
| https://etcho.github.io/poopify-legal/consumer-health-data/ | `consumer-health-data/index.md` (same text as Section 12, as a separate page) |

English is the source language. Translations are managed in Crowdin.

## Publishing a new version

Every published version has its own permanent page (`privacy-policy/1.0/`, `terms-of-use/1.0/`...) next to the current one (`privacy-policy/`, `terms-of-use/`). The app records which version each user accepted, so **a version folder is never edited after it is published**.

1. Edit the current page (`privacy-policy/index.md` or `terms-of-use/index.md`): update **Version** and **Effective date** at the top and add a line to **Version history**.
2. Copy it to a new folder for that version (`privacy-policy/1.1/index.md`) with `permalink: /privacy-policy/1.1/`. For the privacy policy, replace `{% include consumer-health-data.md %}` in the copy with the text of the include, so the copy never changes. If Section 12 changed, edit `_includes/consumer-health-data.md` too.
3. Version numbers are `major.minor`:
   - **minor** (1.0 → 1.1): wording, clarifications, nothing that changes what data is processed or why. The app asks nothing from the user.
   - **major** (1.x → 2.0): material changes. Update `CloudSync.CONSENT` in the app: users who sync see the consent screen again and sync pauses until they accept.
4. Send the new English text to Crowdin and publish the translations (see the translation workflow in the app repository).
