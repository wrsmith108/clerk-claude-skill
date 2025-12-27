# Clerk Authentication Skill for Claude Code

A Claude Code skill for implementing Clerk authentication in Astro/Next.js applications.

## Installation

```bash
git clone https://github.com/wrsmith108/clerk-claude-skill.git ~/.claude/skills/clerk
```

## What's Included

- **Clerk Architecture**: How Clerk works with Astro SSR
- **E2E Testing**: Playwright testing with Clerk's test emails
- **Middleware Patterns**: Route protection and role-based access
- **CI/CD Integration**: GitHub Actions setup for authenticated tests
- **Troubleshooting**: Common auth issues and fixes

## Key Concept

Test user emails **MUST** contain `+clerk_test` for automated testing to work:
- `user+clerk_test_admin@gmail.com` ✅
- `user+admin@gmail.com` ❌

## License

MIT - See [LICENSE](LICENSE)
