# Contributing to BOS Scripts

Thank you for contributing to BOS Scripts.

BOS Scripts follows a structured development workflow to maintain reliable, performant and maintainable FiveM resources.

## Development Standards

All contributions should:

- Follow the existing project structure.
- Follow the project's coding standards.
- Avoid unnecessary dependencies.
- Avoid unnecessary client-side loops.
- Validate sensitive operations server-side.
- Preserve compatibility with the supported framework and dependencies.
- Include documentation where appropriate.
- Avoid breaking existing functionality without prior discussion.

## Pull Requests

Pull requests should:

1. Clearly describe the change.
2. Explain why the change is required.
3. Include relevant testing information.
4. Mention breaking changes.
5. Keep unrelated changes out of the pull request.

## Branches

Recommended branch naming:

- `feature/*` — new functionality
- `fix/*` — bug fixes
- `hotfix/*` — critical production fixes
- `docs/*` — documentation changes
- `refactor/*` — code restructuring

## Commits

Use clear and descriptive commit messages.

Recommended format:

`type: description`

Examples:

- `feat: add sleep recovery system`
- `fix: prevent duplicate item removal`
- `docs: update installation instructions`
- `refactor: optimize client loop`

## Code Quality

Before submitting a pull request:

- Test the affected functionality.
- Check the server console for errors.
- Check the client console for errors.
- Verify resource performance.
- Verify compatibility with the supported environment.

## Security

Do not disclose security vulnerabilities through public issues.

Follow the instructions in `SECURITY.md`.

## Questions

For general questions and support, use the official BOS Scripts support channels.
