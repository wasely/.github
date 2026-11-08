# .github

Default community health files for this account.

GitHub applies anything in here to **every repository on the account that does
not have its own copy** of the same file, at any visibility. A repository that
ships its own `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md` or issue
template keeps using its own; this repo only fills the gaps.

| File | Applies to |
| --- | --- |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | every repo without its own |
| [`SECURITY.md`](SECURITY.md) | every repo without its own |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | every repo without its own |
| [`.github/ISSUE_TEMPLATE/config.yml`](.github/ISSUE_TEMPLATE/config.yml) | the "New issue" chooser, where a repo defines no templates |

So editing a file here changes it everywhere at once. Keep anything
project-specific — setup steps, test commands, the actual architecture — in the
repository it belongs to.

Contributors: **[discord.gg/grokbot](https://discord.gg/grokbot)**.

See [GitHub's documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for the full list of file types that can be defaulted. A `LICENSE` cannot.
