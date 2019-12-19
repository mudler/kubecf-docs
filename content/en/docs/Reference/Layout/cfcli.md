  
---
title: "CF CLI script"
linkTitle: "CF CLI script"
date: 2017-01-05
description: >
  Deploy cf cli into a helper pod from which to then inspect the deployed Kubecf
---

# cf-cli

The `cf_cli.sh` script contained in directory __dev/cf_cli__ is a
temporary helper script that creates a pod with the `cf-cli`
configured and ready to talk to the Kubecf in the cluster.
