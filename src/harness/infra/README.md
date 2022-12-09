# infra

![Version: 0.1.1](https://img.shields.io/badge/Version-0.1.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

Shared Infrastructure components of Harness

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://charts.bitnami.com/bitnami | postgresql | 11.6.16 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| postgresql.auth.database | string | `"overops"` |  |
| postgresql.commonLabels.app | string | `"postgres"` |  |
| postgresql.fullnameOverride | string | `"postgres"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)