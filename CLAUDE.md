# Claude

## Communication
- Reply in the user's language.
- Write code comments and commit messages in English.
- Keep every reply, code comment, commit message and ticket short.
- Prefer bullet lists over paragraphs.

## Commenting
- Do not add comments that repeat what the code already says.
- For any non-standard JavaScript API, read its current docs first, then add an `@see` link to the exact doc page in the file header comment.
- Align Markdown table cells so the pipes line up in the source.
- Never mention AI in commit messages.

## Technologies
- Use [Bun](https://bun.sh) instead of Node.js and Python.
- Use [Elysia](https://elysiajs.com) for HTTP servers.
- Use [Drizzle](https://orm.drizzle.team) with SQLite or Postgres.

## Process
- Follow the official instructions when creating projects or adding plugins and components. Your knowledge is outdated. Still run every step with Bun, even when the instructions use npm, Node.js or Python.
