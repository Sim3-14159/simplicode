# Contributing to $\color{red}\text{SIMpliCode}$ 🥳

## 🎬 Getting Started 
[Fork this repository](https://github.com/Sim3-14159/simplicode/fork) and start working!

## 📄 Code of Conduct
Please read and follow the [Code of Conduct](./CODE_OF_CONDUCT.md). In short: be respectful, inclusive, and constructive.

## How to Contribute
### Reporting Bugs
- Check existing [issues](https://github.com/your-org/simplicode/issues) first.
- Use the bug template and include:
  - Browser/OS versions (I am testing this in Safari, which is pretty much the worst possible, so you shouldn't have any problems)
  - Steps to reproduce
  - Screenshots if helpful

### Pull Requests
1. Create a feature branch: `git checkout -b feat/autocomplete-improvements`
2. Write or update tests for any new logic.
3. Run the linter and tests: `npm run lint && npm test`
4. Commit with clear messages (follow [Conventional Commits](https://www.conventionalcommits.org/)).
5. Push and open a PR. Our CI will run automated checks; address any failures promptly.

## Development Workflow
- The project is organized into:
  - `src/` – TypeScript source for the editor core and AI module
  - `public/` – Static assets and sample HTML templates
  - `tests/` – Jest + Playwright suites
- Hot-reload is enabled; save a file and the preview updates instantly.
- For AI features, set your `OPENAI_API_KEY` in a local `.env` file.

## Style Guide
- Use Prettier defaults (2-space indent, single quotes).
- Prefer functional components and hooks in React parts.
- Prefix AI-related utilities with `ai-` for clarity.

## Documentation
- Update `README.md` or `docs/` if your change affects user workflows.
- Inline JSDoc comments are encouraged for exported functions.

## Questions?
Raise an issue addressed to **<u>@Sim3-14159</u>**
