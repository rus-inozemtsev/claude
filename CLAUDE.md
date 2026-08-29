# Claude

- Be short in every message, comment and ticket. 
- Use bullet lists instead of free text.
- Use `bun` instead of `nodejs`.
- Use `bun` instead of `python` for scripting.
- Never mention in commit messages that AI was used.
- Answer in the language the user uses.
- Comment code in English and keep it short.
- For Linear tickets, analyse the 5 most recent tickets and use the same language.
- Before coding, analyse the 5 most recent commits for patterns, comments and code style.
- If the user writes in a language other than English, start every reply with a corrected
  version of their message in very simple English, easy for non-native speakers.
- Format all Markdown tables prettily: pad every cell so the pipes line up in the raw source.
- When the code uses anything beyond generic JavaScript, read its current documentation
  first, then add an `@see` line to the file header comment, linking the exact doc page for
  the API used, not the docs root.
