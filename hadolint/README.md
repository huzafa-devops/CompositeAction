<!-- action-docs-description action="action.yml" -->
## Description

Action that runs Hadolint Dockerfile linting tool
<!-- action-docs-description action="action.yml" -->

<!-- action-docs-inputs action="action.yml" -->
## Inputs

| name | description | required | default |
| --- | --- | --- | --- |
| `docker_file` | <p>Name of the dockerfile</p> | `true` | `Dockerfile` |
| `recursive_enabled` | <p>Search for specified dockerfile recursively, from the project root</p> | `true` | `""` |
| `config_file` | <p>Custom path to a Hadolint config file</p> | `false` | `""` |
<!-- action-docs-inputs action="action.yml" -->

<!-- action-docs-outputs action="action.yml" -->

<!-- action-docs-outputs action="action.yml" -->

<!-- action-docs-runs action="action.yml" -->
## Runs

This action is a `composite` action.
<!-- action-docs-runs action="action.yml" -->