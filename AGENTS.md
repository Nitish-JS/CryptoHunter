# AGENTS.md - CryptoHunter

## Development
- Requires Node.js ≥14.
- Install packages with `npm install --legacy-peer-deps`.
- Use `npm start` for the dev server.
- Before committing, verify the project builds by running `npm run build`.
- If any tests are present, run `npm test` as well.

## Style
- Use 2-space indentation and include semicolons.
- Favor React functional components as in existing files.
- Apply Prettier (or similar) to maintain consistent formatting.

## Commit messages
- Follow the structure `<scope>: <brief summary>`, e.g.
  `Header: fix currency selector`.

## Pull requests
- Ensure `npm run build` succeeds and cite any test output in the PR body.
