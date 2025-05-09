## sonobuoy logs

Dumps the logs of the currently running Sonobuoy containers for diagnostics

```
sonobuoy logs [flags]
```

### Options

```
      --context string          Context in the kubeconfig to use.
  -f, --follow                  Continue following the logs of the Sonobuoy created containers.
  -h, --help                    help for logs
      --kubeconfig Kubeconfig   Path to explicit kubeconfig file.
  -n, --namespace string        The namespace to run Sonobuoy in. Only one Sonobuoy run can exist per namespace simultaneously. (default "sonobuoy")
  -p, --plugin string           Show logs only for a specific plugin. If 'sonobuoy' is provided, only shows the aggregator logs.
```

### Options inherited from parent commands

```
      --level level   Log level. One of {panic, fatal, error, warn, info, debug, trace} (default info)
```

### SEE ALSO

* [sonobuoy](sonobuoy.md)	 - Generate reports on your Kubernetes cluster by running plugins

###### Auto generated by spf13/cobra on 18-Feb-2025
