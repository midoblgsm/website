---
---

## kubectl explain

Documentation of resources

### Synopsis



Documentation of resources.

Valid resource types include:
   * clusters (valid only for federation apiservers)
   * componentstatuses (aka 'cs')
   * configmaps (aka 'cm')
   * daemonsets (aka 'ds')
   * deployments (aka 'deploy')
   * events (aka 'ev')
   * endpoints (aka 'ep')
   * horizontalpodautoscalers (aka 'hpa')
   * ingress (aka 'ing')
   * jobs
   * limitranges (aka 'limits')
   * nodes (aka 'no')
   * namespaces (aka 'ns')
   * petsets (alpha feature, may be unstable)
   * pods (aka 'po')
   * persistentvolumes (aka 'pv')
   * persistentvolumeclaims (aka 'pvc')
   * quota
   * resourcequotas (aka 'quota')
   * replicasets (aka 'rs')
   * replicationcontrollers (aka 'rc')
   * secrets
   * serviceaccounts (aka 'sa')
   * services (aka 'svc')


```
kubectl explain RESOURCE
```

### Examples

```

# Get the documentation of the resource and its fields
kubectl explain pods

# Get the documentation of a specific field of a resource
kubectl explain pods.spec.containers
```

### Options

```
      --include-extended-apis   If true, include definitions of new APIs via calls to the API server. [default true] (default true)
      --recursive               Print the fields of fields (Currently only 1 level deep)
```

### Options inherited from parent commands

```
      --alsologtostderr value          log to standard error as well as files
      --as string                      Username to impersonate for the operation
      --certificate-authority string   Path to a cert. file for the certificate authority
      --client-certificate string      Path to a client certificate file for TLS
      --client-key string              Path to a client key file for TLS
      --cluster string                 The name of the kubeconfig cluster to use
      --context string                 The name of the kubeconfig context to use
      --insecure-skip-tls-verify       If true, the server's certificate will not be checked for validity. This will make your HTTPS connections insecure
      --kubeconfig string              Path to the kubeconfig file to use for CLI requests.
      --log-backtrace-at value         when logging hits line file:N, emit a stack trace (default :0)
      --log-dir value                  If non-empty, write log files in this directory
      --logtostderr value              log to standard error instead of files
      --match-server-version           Require server version to match client version
  -n, --namespace string               If present, the namespace scope for this CLI request
      --password string                Password for basic authentication to the API server
  -s, --server string                  The address and port of the Kubernetes API server
      --stderrthreshold value          logs at or above this threshold go to stderr (default 2)
      --token string                   Bearer token for authentication to the API server
      --user string                    The name of the kubeconfig user to use
      --username string                Username for basic authentication to the API server
  -v, --v value                        log level for V logs
      --vmodule value                  comma-separated list of pattern=N settings for file-filtered logging
```



###### Auto generated by spf13/cobra on 24-Oct-2016





<!-- BEGIN MUNGE: GENERATED_ANALYTICS -->
[![Analytics](https://kubernetes-site.appspot.com/UA-36037335-10/GitHub/docs/user-guide/kubectl/kubectl_explain.md?pixel)]()
<!-- END MUNGE: GENERATED_ANALYTICS -->