---
title: Create Istio Mixer rules
overview: Create Istio Mixer rules

order: 10

bodyclass: docs
layout: docs
type: markdown
---
## istioctl mixer rule create

Create Istio Mixer rules

### Synopsis


Create Istio Mixer rules

```
istioctl mixer rule create <scope> <subject>
```

### Options

```
  -f, --file string   Input file with contents of the mixer rule
```

### Options inherited from parent commands

```
  -c, --kubeconfig string                Use a Kubernetes configuration file instead of in-cluster configuration
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
  -m, --mixer string                     Address of the mixer API server as <host>:<port>
  -n, --namespace string                 Select a Kubernetes namespace (default "default")
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [istioctl mixer rule](istioctl_mixer_rule.html)	 - Istio Mixer Rule configuration
