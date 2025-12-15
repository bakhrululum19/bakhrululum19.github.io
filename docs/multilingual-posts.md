## Multilingual posts

- English content lives at `content/posts/<slug>/index.md`.
- Indonesian translations live in the same bundle as `index.id.md`.
- Section landing pages are controlled by `content/posts/_index.en.md` and `_index.id.md`.

### URL layout

- English: `https://bakhrululum19.github.io/posts/<slug>/`
- Bahasa: `https://bakhrululum19.github.io/id/posts/<slug>/`

The `[permalinks]` block in `config.toml` forces this scheme so Hugo will keep generating the same structure.

### Adding a new article

1. Create a new folder under `content/posts/<slug>/`.
2. Add the English Markdown file named `index.md`.
3. Add the Bahasa version as `index.id.md` (optional, but Hugo will pick it up automatically).
4. Keep supporting assets inside the same bundle so the two languages can share images.
