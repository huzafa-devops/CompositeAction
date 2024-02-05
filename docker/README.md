<!-- action-docs-description action="action.yml" -->
## Description

Scans container images for vulnerabilities with Trivy and pushed image to docker hub
<!-- action-docs-description action="action.yml" -->

<!-- action-docs-inputs action="action.yml" -->
## Inputs

| name | description | required | default |
| --- | --- | --- | --- |
| `dockerhub_username` | <p>Username for image registry</p> | `true` | `""` |
| `dockerhub_access_token` | <p>dockerhub access token</p> | `true` | `""` |
| `image_name` | <p>Name of the image to push</p> | `true` | `""` |
| `folder_name` | <p>Name of the folder containing the Dockerfile</p> | `true` | `""` |
| `tag` | <p>Image tag. Default is latest</p> | `false` | `latest` |
<!-- action-docs-inputs action="action.yml" -->

<!-- action-docs-outputs action="action.yml" -->

<!-- action-docs-outputs action="action.yml" -->

<!-- action-docs-runs action="action.yml" -->
## Runs

This action is a `composite` action.
<!-- action-docs-runs action="action.yml" -->