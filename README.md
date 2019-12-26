# Terraform module for GitLab auto scaling runners on Azure

[![License](https://img.shields.io/badge/license-Apache-green.svg?style=flat)](https://raw.githubusercontent.com/lean-delivery/tf-module-azure-gitlab-runner/master/LICENSE)
[![Build Status](https://travis-ci.org/lean-delivery/tf-module-azure-gitlab-runner.svg?branch=master)](https://travis-ci.org/lean-delivery/tf-module-azure-gitlab-runner)

## Description

This repo contains a terraform module to run a [GitLab CI autoscaling runner](https://docs.gitlab.com/runner/configuration/autoscale.html)

## Usage

In order to run terraform configurations [Azure provider](https://www.terraform.io/docs/providers/azurerm/index.html) should be initialized. It's possible to configure it in a few different ways.

For example, to store credentials as environment variables:
```sh
$ export ARM_CLIENT_ID="00000000-0000-0000-0000-000000000000"
$ export ARM_CLIENT_SECRET="00000000-0000-0000-0000-000000000000"
$ export ARM_SUBSCRIPTION_ID="00000000-0000-0000-0000-000000000000"
$ export ARM_TENANT_ID="00000000-0000-0000-0000-000000000000"
```

### Conditional creation

### Known issues / Limitations

### Code included in this module

### Examples

## Inputs

## Outputs

## Tests

## Terraform versions

## Contributing
Thank you for your interest in contributing! Please refer to [CONTRIBUTING.md](https://github.com/lean-delivery/tf-module-azure-gitlab-runner/CONTRIBUTING.md) for guidance.

## License

Apache

## Authors

authors:
  - Lean Delivery Team <team@lean-delivery.com>
