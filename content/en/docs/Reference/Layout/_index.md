---
title: "Project Layout"
linkTitle: "Project Layout"
date: 2017-01-05
description: >
  What are the files in the KubeCF project?
---

The important directories of the KubeCF sources, and their contents
are shown in the table below. Each directory entry links to the
associated documentation, if we have any.

|Directory                                                              |Content                                                |
|---                                                                    |---                                                    |
|__top__                                                                |Documentation entrypoint, License,                     |
|                                                                       |Main workspace definitions.                            |
|__top__/.../README.md                                                  |Directory-specific local documentation.                |
|[__top__/bosh/releases](/docs/reference/layout/patches/) |Support for runtime patches of a kubecf deployment.    |
|__top__/doc                                                            |Global documentation.                                  |
|[__top__/dev/cf_deployment/bump](/docs/reference/layout/bump/)                |Tools to support updating the cf deployment            |
|                                                                       |manifest used by kubecf.                               |
|[__top__/dev/cf_cli](/docs/reference/layout/cfcli/)                                        |Deploy cf cli into a helper pod from which to then     |
|                                                                       |inspect the deployed Kubecf                            |
|[__top__/dev/kube](/docs/reference/layout/kube/)                                      |Tools to inspect kube clusters and kubecf deployments. |
|[__top__/dev/linters](/docs/reference/layout/linters/)                                      |Tools for statically checking the kubecf sources.      |
|[__top__/dev/minikube](/docs/reference/layout/minikube/)                               |Targets to manage a local kubernetes cluster.          |
|                                                                       |Minikube based.                                        |
|[__top__/dev/kind](/docs/reference/layout/kind/)                                       |Targets to manage a local kubernetes cluster.          |
|                                                                       |KinD based (Kube-in-Docker).                           |
|[__top__/dev/kubecf](/docs/reference/layout/kubecf/)                          |Kubecf chart configuration, and targets for            |
|                                                                       |local chart application.                               |
|__top__/deploy/helm/kubecf                                             |Templates and assets wrapping a CF deployment          |
|                                                                       |manifest into a helm chart.                            |
|__top__/rules                                                          |Supporting bazel definitions.                          |
|[__top__/testing](/docs/reference/layout/testing/)                                            |Bazel targets to run CF smoke and acceptance tests.    |