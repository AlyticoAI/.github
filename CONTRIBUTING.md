# Contributing

This is a private, proprietary AlyticoAI codebase. Access is granted only to
employees, contractors, and invited collaborators under a signed agreement
(employment/contractor contract or CLA). See [LICENSE](LICENSE).

## Branching

Branch off the default branch using one of:

| Prefix      | Use for                                              |
|-------------|-------------------------------------------------------|
| `feature/`  | New functionality                                     |
| `fix/`      | Non-urgent bug fix                                    |
| `hotfix/`   | Urgent production fix                                  |
| `release/`  | Release stabilization branch                           |
| `chore/`    | Tooling, deps, docs, CI — no product behavior change    |

Branch names not matching one of these prefixes are rejected by the repo's
branch-naming rule.

## Pull requests

- The default branch is protected: no direct pushes, no force-pushes, no
  deletions — every change lands via a reviewed, approved PR.
- Fill out the PR template completely, including testing evidence.
- Only members of `@AlyticoAI/code-owners` can complete a merge into the
  protected branch, once required reviews and checks pass.
- Merges are squash-only — keep your branch's commit history readable, since
  it becomes the final commit message.
- Resolve all review conversations before requesting merge.

## Reporting a security issue

See [SECURITY.md](SECURITY.md) — do not open a public issue for vulnerabilities.
