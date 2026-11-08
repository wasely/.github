# Security Policy

## Reporting a vulnerability

**Please do not open a public issue for a security problem.**

Use GitHub's private reporting instead: go to the repository's **Security** tab
and choose **Report a vulnerability**. That opens a private advisory only the
maintainers can see, and it lets us credit you when the fix ships.

If private reporting is not available on that repository, send a direct message
to `blix` in the [Discord](https://discord.gg/grokbot) and we will open the
advisory for you.

## What to include

Whatever you have is better than nothing, but a report is much faster to act on
when it says:

- which repository and which version, commit, or release
- what an attacker can do with it, in one sentence
- the steps to reproduce it, or a short script
- anything that limits it, such as needing a local file or a signed-in session

## What to expect

- An acknowledgement within **three days**.
- An assessment, and either a fix or a reason we think it is not exploitable,
  within **14 days** for anything we can reproduce.
- Credit by name in the advisory and the release notes, unless you ask us not
  to.

## Scope

These projects are mostly local-first desktop apps, browser extensions, and CLI
tools that run on your own machine with your own API keys. The things we most
want to hear about:

- code execution from input a project treats as data — a video, a transcript, a
  pasted URL, a note, a reference image
- a path that escapes the directory a project is supposed to stay inside
- an API key, token, or cookie written somewhere it can be read by another
  program, logged, or sent off the machine
- a browser extension content script that can be driven by the page it is
  injected into

Out of scope: findings that need an attacker to already control your machine or
your GitHub account, missing hardening with no demonstrated impact, and raw
output from an automated scanner with nothing shown to be exploitable.
