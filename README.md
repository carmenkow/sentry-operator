# Sentry Operator

Kubernetes Operator that manage buckets and users on a Sentry server.

[![Docker Pulls](https://img.shields.io/docker/pulls/robotinfra/sentry-operator.svg?maxAge=604800)](https://hub.docker.com/r/robotinfra/sentry-operator)

## Develop

- Open directory in [VSCode as a container](https://code.visualstudio.com/docs/remote/containers).
- Configure Kubernetes client in the container, such as create a `/root/.kube/config` file.
- Run task `Install CRDs` to create CRD.

You can run operator by running task `Run Operator`.

## Installation

Install helm chart `sentry-operator` version `0.1.3` in repository `https://robotinfra-charts.sgp1.digitaloceanspaces.com/`.

Values can be found at `deploy/values.yaml`.

## Usage
