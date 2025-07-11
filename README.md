# Setup Maestro

[![GitHub Release](https://img.shields.io/github/v/release/ryohidaka/action-setup-maestro)](https://github.com/ryohidaka/action-setup-maestro/releases/)
[![Test Action](https://github.com/ryohidaka/action-setup-maestro/actions/workflows/test.yml/badge.svg)](https://github.com/ryohidaka/action-setup-maestro/actions/workflows/test.yml)

GitHub Actions to setup Maestro CLI.

## Usage

```yml
on: [push]

jobs:
  setup-maestro:
    runs-on: ubuntu-latest
    steps:
      - uses: ryohidaka/action-setup-maestro@v1
```

## Inputs

| Input | Description | Required | Default |
| ----- | ----------- | -------- | ------- |
| ``    |             | ✅       | ``      |
