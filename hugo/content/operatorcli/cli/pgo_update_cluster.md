---
title: "pgo_update_cluster"
---
## pgo update cluster

Update a PostgreSQL cluster

### Synopsis

Update a PostgreSQL cluster. For example:

    pgo update cluster all --autofail=false
    pgo update cluster mycluster --autofail=true

```
pgo update cluster [flags]
```

### Options

```
      --autofail string   If set, will cause the autofail label on the pgcluster CRD for this cluster to be updated to either true or false, valid values are true or false.
  -h, --help              help for cluster
      --no-prompt         No command line confirmation.
  -s, --selector string   The selector to use for cluster filtering.
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo update](/operatorcli/cli/pgo_update/)	 - Update a cluster

###### Auto generated by spf13/cobra on 26-Apr-2019