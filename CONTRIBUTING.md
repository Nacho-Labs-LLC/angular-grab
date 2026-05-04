# Contributing to angular-grab

Thanks for your interest in contributing! Here's how to get started.

## Getting Started

```bash
git clone https://github.com/Nacho-Labs-LLC/angular-grab.git
cd angular-grab
pnpm install
pnpm build
pnpm test
```

## Development Workflow

1. Fork the repo and create a feature branch from `main`
2. Make your changes
3. Add or update tests for any new behavior
4. Run `pnpm build` and `pnpm test` to verify
5. Open a pull request against `main`

## Project Structure

```
packages/
  core/           # Main angular-grab library
  mcp-server/     # MCP server for AI agent integration
```

## Code Style

- TypeScript strict mode
- Prefer early returns over deep nesting
- No comments explaining *what* — only *why* when non-obvious
- Keep functions small and focused

## Tests

Every new feature or bug fix should include tests.

```bash
pnpm test
```

## Pull Requests

- Keep PRs focused — one feature or fix per PR
- Include a clear description of what changed and why
- Link to a related issue if one exists
- All tests must pass and the build must succeed

## Reporting Issues

Use [GitHub Issues](https://github.com/Nacho-Labs-LLC/angular-grab/issues) for bugs and feature requests.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](./LICENSE).
