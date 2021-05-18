# Cloud Native Recipes

[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy)

This example shows how to develop a cloud native application using [Okteto Cloud](https://cloud.okteto.com), Docker Compose, Go, Vue and the [Okteto CLI](https://github.com/okteto/okteto).

This application takes advantage of the following parts of Okteto:
1. [Okteto Pipelines](https://okteto.com/docs/cloud/deploy-from-git) to automatically deploy your development environment
1. [Integration with Docker Compose](https://okteto.com/docs/reference/stacks) with Okteto Cloud extensions to automatically define public endpoints
1. [Develop on Okteto Button](https://okteto.com/docs/cloud/develop-on-okteto-button)
1. [Preview Environments](https://okteto.com/docs/cloud/preview-environments/preview-environments-github) for every PR (check [.github/workflows/preview.yaml](.github/workflows/preview.yaml))
1. [Okteto CLI](https://github.com/okteto/okteto) to develop directly in Okteto Cloud

Both the api and frontend services are configured to be used with `okteto up`, try them out!