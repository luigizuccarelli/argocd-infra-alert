# ArgoCD-Alert-Cron-Deploy

## Overview

All the necessary yaml files to deploy the kubectl container to push logs to elsticsearch for all namespaces

## Folder structure

The folder structure is as follows :

```bash

      --- environments
      |     |
      |     --- overlays
      |           |
      |           --- prod
      |                 |
      |                 --- namespace
      |                 |     |
      |                 |     --- limit-range.yaml
      |                 |     --- namespace.yaml
      |                 |     --- resource-quota.yaml
      |                 --- shared
      |                 |     |
      |                 |     --- shared-resousrce (i.e pv)
      |                 |
      |                 --- kustermization.yaml
      |
      --- manifests
            |
            --- services
                  |
                  |
                  --- base
                        |
                         --- alert-configmap.yaml
                             alert-eventscron-deploy.yaml

```
            

