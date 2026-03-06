# Contributing Guide

Thank you for contributing to ShopApp Angular.

## Branching

- Create feature branches from `master`.
- Use clear branch names, for example: `feature/admin-product-filter`.

## Commit Convention

Use short, meaningful commit messages with prefixes:

- `feat:` new feature
- `fix:` bug fix
- `refactor:` internal code improvements
- `docs:` documentation updates
- `chore:` maintenance tasks
- `ci:` pipeline/workflow updates

## Local Validation Before Push

Run these commands before opening a pull request:

```bash
corepack pnpm run build
corepack pnpm run test:ci
```

## Pull Request Checklist

- [ ] Scope is focused and small
- [ ] Build passes locally
- [ ] Tests pass locally
- [ ] README/docs updated if behavior changed
