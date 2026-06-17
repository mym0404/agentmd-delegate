# I Code By Hand

![I Code By Hand hero](./ogimage.png)

`AGENTS.md` or `CLAUDE.md` are powerful ways to instruct AI agents.

## Usecase 1: You cannot add agent instructions to the repository.

Some repositories should not gain new agent-instruction files. Keep your personal repo guidance outside the project tree instead.

## Usecase 2: You're an enthusiastic open-source contributor of a legacy project.

Adding `AGENTS.md` or `CLAUDE.md` to the repo is out of your remit, right? Don't worry.

Stop trying to create PR adding these files and start using the skill instead.

## What it is

An agent skill that manages `AGENTS.md` or `CLAUDE.md` guidance outside of the repo.

Your outside repository knowledge is stored under a repo-specific directory:

```text
~/.icodebyhand/{owner}/{repo}/
```

Use `$i-code-by-hand` to manage repo-specific instructions outside of the repo.

## Install

```sh
npx skills add mym0404/i-code-by-hand -g -s i-code-by-hand
```

## Notes

- Project-local instructions still take priority.
- Missing global memory entry points are not created automatically.
