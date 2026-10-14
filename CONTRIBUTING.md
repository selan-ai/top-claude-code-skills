# Contributing

README.md is generated. Once a day a script reads GitHub, ranks the list again and replaces the
whole file, so the list changes through what goes into it, never through an edit.

## How a skill gets in

The daily run finds candidates two ways: every repository tagged with one of the GitHub topics
named under *How it is ranked* in the README, and every repository linked from the curated lists
it reads. Tagging your repository is the surest way to be found.

A candidate is listed when it is among the 15 with the most stars that pass every check:

- **A licence.** GitHub can detect one at its root, or at least 90% of its skill folders carry a
  licence file of their own.
- **Alive.** It has a commit in the last six months and is not archived.
- **A README that says what it does**, clearly enough to describe it in one sentence.
- **It is a skill.** It ships at least one `SKILL.md` file, and it is not a fork, an app, an MCP
  server or a course.
- **Real stars.** Stars that came without the forks and watchers real use brings are left out.

The full method, with what the week and month rankings weigh, is on
[selan.ai](https://selan.ai/top/claude-code-skills#method).

## Suggesting a skill

Open an issue with the
[suggestion form](https://github.com/selan-ai/top-claude-code-skills/issues/new?template=suggest-a-skill.yml):
the repository's URL, what it does and why it belongs. It is checked against the rules above, and
the answer goes on the issue. Whether a skill that passes is listed depends on its stars.

## Pull requests

A pull request that edits README.md is closed, with thanks: the next daily run would overwrite it.
If it named a skill, it is read as a suggestion.
