# Claude
- Use `https://bun.sh` instead of Node.js and Python.

- Reply in the user's language.
- Keep every message, comment and ticket short.
- Prefer bullet lists over paragraphs.
- Write code comments in English.
- Do not add comments that repeat what the code already says.
- Wrap all text and code at 80 characters. This does not apply to Markdown
  tables.
- Align Markdown table cells so the pipes line up in the source.
- Never mention AI in commit messages.

- Follow the official instructions when creating projects or adding plugins
  and components. Your knowledge is outdated. Still run every step with Bun,
  even when the instructions use npm, Node.js or Python.
- For any non-standard JavaScript API, read its current docs first, then add
  an `@see` link to the exact doc page in the file header comment.
