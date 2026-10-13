# gc3-webplatform default templates

GitHub uses the PR and issue templates in `.github/` for every repository in gc3-webplatform
that has none of its own. GitHub reads them only while this repository is public and named
`.github`.

## Issue forms

Each form sets one GitHub issue type, so the kind of issue is the type, never a label.

| Form | File | Issue type |
| --- | --- | --- |
| Bug report | `bug_report.yml` | Bug |
| Feature request | `feature_request.yml` | Feature |
| Task | `task.yml` | Task |
| Documentation | `documentation.yml` | Documentation |
| Experimentation | `experimentation.yml` | Experimentation |
| Maintenance | `maintenance.yml` | Maintenance |
| Performance | `performance.yml` | Performance |

- The `type:` in a form must match an issue type defined in the organization, or GitHub drops it.
- Another organization can copy `.github/ISSUE_TEMPLATE/` as is, once it has the same seven
  issue types.
