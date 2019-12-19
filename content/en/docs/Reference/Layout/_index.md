---
title: "Project Layout"
linkTitle: "Project Layout"
date: 2017-01-05
description: >
  What are the files in the KubeCF project?
---

## Source Organization

The important directories of the kubecf sources, and their contents
are shown in the table below. Each directory entry links to the
associated documentation, if we have any.

|Directory                                                              |Content                                                |
|---                                                                    |---                                                    |
|__top__                                                                |Documentation entrypoint, License,                     |
|                                                                       |Main workspace definitions.                            |
|__top__/.../README.md                                                  |Directory-specific local documentation.                |
|[__top__/bosh/releases](../bosh/releases/pre_render_scripts/README.md) |Support for runtime patches of a kubecf deployment.    |
|__top__/doc                                                            |Global documentation.                                  |
|[__top__/dev/cf_deployment/bump](cf_deployment/bump.md)                |Tools to support updating the cf deployment            |
|                                                                       |manifest used by kubecf.                               |
|[__top__/dev/cf_cli](cf_cli.md)                                        |Deploy cf cli into a helper pod from which to then     |
|                                                                       |inspect the deployed Kubecf                            |
|[__top__/dev/kube](inspection.md)                                      |Tools to inspect kube clusters and kubecf deployments. |
|[__top__/dev/linters](linters.md)                                      |Tools for statically checking the kubecf sources.      |
|[__top__/dev/minikube](kube/minikube.md)                               |Targets to manage a local kubernetes cluster.          |
|                                                                       |Minikube based.                                        |
|[__top__/dev/kind](kube/kind.md)                                       |Targets to manage a local kubernetes cluster.          |
|                                                                       |KinD based (Kube-in-Docker).                           |
|[__top__/dev/kubecf](../dev/kubecf/README.md)                          |Kubecf chart configuration, and targets for            |
|                                                                       |local chart application.                               |
|__top__/deploy/helm/kubecf                                             |Templates and assets wrapping a CF deployment          |
|                                                                       |manifest into a helm chart.                            |
|__top__/rules                                                          |Supporting bazel definitions.                          |
|[__top__/testing](tests.md)                                            |Bazel targets to run CF smoke and acceptance tests.    |