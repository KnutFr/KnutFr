# KnutFr agent instructions

<!-- python-automation:start -->

## Agent automation

- Use Python for agent-authored scripts, helpers, file operations and automation. Launch with `py -3` on Windows or `python3` elsewhere; use `subprocess` argument lists with explicit working directories and environments.
- Keep application languages, generated/vendor files and necessary native/container entrypoints. Migrate a touched PowerShell workflow with its callers, docs and meaningful checks before using it; preserve its safety gates.
- Do not create PowerShell helpers, recommend PowerShell script execution, or change Windows execution policy/security settings.
- Track remaining native workflow migrations and platform validation in [the cross-repository checklist](https://github.com/KnutFr/monorepo/issues/486). Instructions alone do not establish runtime parity.

<!-- python-automation:end -->
