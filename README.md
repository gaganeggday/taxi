# The Taxi Application


## About

This  the source code, deployment manifests and CI/CD pipelines for the taxi applicati

## Application Source code

The application source code resides in the `src` director

## Pipelines

The [pipelines](../pipelines) that power the CI and CD jobs for this repository have been defined as Tekton Tasks & Tekton Pipeline definitions

### CI

The CI pipeline does the following:

- Validates any changes made to [deployment manifests](../deploy)
- Builds an image and pushes it to the registry

### CD

The CD pipeline deploys the kubernetes manifests of the `taxi` app to the `dev` environm
trigger
Just to check if the pipelines work, just another change
Another change
