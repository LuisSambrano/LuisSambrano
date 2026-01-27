# The Daily Grind: Active Contribution Strategy

To keep your GitHub dashboard green and active without burnout, follow this protocol.

## 1. The "Today I Learned" (TIL) Repository

Create a public repository called `til` or `knowledge-base`.

- **Concept**: Every time you learn something small (Rust syntax, a React hook trick, a terminal command), write a small markdown file.
- **Why**: It counts as a contribution, it builds a knowledge base, and it shows continuous learning.
- **Format**: `til/rust/memory-safety.md`, `til/react/use-optimistic.md`.

## 2. Review & Refactor (The 15-Minute Rule)

If you don't have code to write, dedicate 15 minutes to:

- **Review**: Read code in `Work` repos. Fixing a typo in a comment counts as a commit.
- **Dependencies**: Run `npm update` on a project and commit the lockfile.
- **Docs**: Translate one paragraph of a `README` to Spanish/English.

## 3. Atomic Commits

Don't wait 3 days to push a big feature.

- **Bad**: "Complete Authentication" (1 commit).
- **Good**: "feat: add login form UI", "feat: implement auth service", "test: add unit tests for auth". (3 commits).

## 4. Issues Management

- Open issues for yourself in your projects (`invoice-zero`, `dolar-api`).
- "Refactor GlassCard component", "Update dependencies".
- Closing an issue via a commit (`Closes #12`) counts heavily for the algorithm.

---

## Your Weekly Routine

- **Mon-Thu**: Feature work on `invoice-zero` or `Work` projects.
- **Fri**: Maintenance (Updates, Refactors, Docs).
- **Sat/Sun**: Optional `TIL` entry if you read an article.
