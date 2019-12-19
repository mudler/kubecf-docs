  
---
title: "KubeCF"
linkTitle: "KubeCF"
date: 2017-01-05
description: >
   Kubecf chart configuration, and targets for local chart application.
---

The target defined in directory __dev/kubecf__ is used to apply the
rendered Helm template to a Kubernetes cluster.

__Attention__: While any files matching the glob pattern
`*values.yaml` and found in this directory are ignored by git, they
are used by Bazel to render the SCF chart before applying to the
cluster with kubectl.
