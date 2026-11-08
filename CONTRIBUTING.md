# Contributing

This is the shared guide. If the repository you are looking at has its own
`CONTRIBUTING.md`, that one wins — it has the real setup and test commands.

## Finding something to work on

Every repository keeps a set of small, scoped issues for people who have not
worked on it before. Each one names the files to change, what the current
behaviour is, and what "done" looks like.

- **Start here:** the repository's **Contribute** page —
  `github.com/<owner>/<repo>/contribute` — or its
  `good first issue` label.
- **Bigger pieces:** the `help wanted` label.

**Comment on the issue to claim it.** That is the whole process; you do not need
to ask permission twice, and it stops two people building the same thing.

## Before you open a pull request

1. Run whatever the repository uses to check itself. Most have a single command
   for it — `npm run validate`, `npm test`, `pytest`, or a `scripts/` entry
   point. The repository's own `CONTRIBUTING.md` or `package.json` says which.
2. **Run the formatter if there is one.** Several of these repositories fail CI
   on formatting alone, and it is the most common reason a first pull request
   goes red.
3. Keep the change to one thing. A small pull request that does one thing gets
   merged; a large one that does five waits for review.

## What to expect back

- A review within **a couple of days**. If it goes quiet, say so in the
  [Discord](https://discord.gg/grokbot) and it will get looked at.
- Honest feedback. If something is not going to be merged, you will be told why
  rather than left waiting.
- **Credit by name** in the release notes.

## The Discord

**[discord.gg/grokbot](https://discord.gg/grokbot)** is the one server for every
repository here. It is worth joining before you open a pull request:

- 🟢 **Claim an issue and it is yours.** Say which one in `#contributors` and it
  gets assigned to you.
- 🏷️ **A contributor role** on the server once your first pull request is
  merged.
- 🗺️ **A say in what gets built.** The roadmap is argued out there before it
  becomes issues.
- 🙋 **A human to ask.** Stuck on setup, or unsure whether an idea is even
  wanted? Faster than waiting on an issue thread.

## Code of conduct

By taking part you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).

## Security

Found a vulnerability? Do not open a public issue — see
[SECURITY.md](SECURITY.md).
