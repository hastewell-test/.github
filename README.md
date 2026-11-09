# .github

The organization's **public** defaults. GitHub serves every file here to each repo in `hastewell-test` that doesn't have its own copy.

| Path | What it gives every repo |
|---|---|
| `ISSUE_TEMPLATE/` | the issue forms (Bug, Feature, Task), each setting its issue type |
| `pull_request_template.md` | the pull request description |
| `CONTRIBUTING.md` | the contribution guide |
| `workflow-templates/` | starter workflows under **Actions → New workflow**, "By Hastewell Test" |
| `profile/README.md` | the public org profile |

## Rules for this repo

- **Everything here is public.** Nothing internal or sensitive goes in it. The members-only landing page lives in `.github-private`.
- A repo that adds its own `.github/ISSUE_TEMPLATE/` loses **all** of these issue forms, so repos keep the defaults unless they really need their own.
