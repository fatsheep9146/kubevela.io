---
title: vela status
---

Show status of an application.

### Synopsis

Show status of vela application.

```
vela status APP_NAME [flags]
```

### Examples

```
vela status APP_NAME
```

### Options

```
  -c, --component string       filter service endpoints by component name
  -d, --detail                 display the realtime details of application resources
      --detail-format string   the format for displaying details. Can be one of inline (default), wide, list, table, raw. (default "inline")
  -p, --endpoint               show all service endpoints of the application
  -e, --env string             specify environment name for application
  -h, --help                   help for status
  -n, --namespace string       specify the Kubernetes namespace to use
  -s, --svc string             service name
  -t, --tree                   display the application resources into tree structure
```

### Options inherited from parent commands

```
  -y, --yes   Assume yes for all user prompts
```

### SEE ALSO



#### Go Back to [CLI Commands](vela) Homepage.


###### Auto generated by spf13/cobra on 19-Apr-2022, refer to [script in KubeVela](https://github.com/oam-dev/kubevela/tree/master/hack/docgen).
