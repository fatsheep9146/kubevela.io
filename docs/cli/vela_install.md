---
title: vela install
---

Installs or Upgrades Kubevela control plane on a Kubernetes cluster.

### Synopsis

The Kubevela CLI allows installing Kubevela on any Kubernetes derivative to which your kube config is pointing to.

```
vela install [flags]
```

### Options

```
  -d, --detail             show detail log of installation (default true)
  -f, --file string        custom the chart path of KubeVela control plane
  -h, --help               help for install
  -n, --namespace string   namespace scope for installing KubeVela Core (default "vela-system")
  -r, --reuse              will re-use the user's last supplied values. (default true)
      --set stringArray    set values on the command line (can specify multiple or separate values with commas: key1=val1,key2=val2)
  -v, --version string      (default "UNKNOWN")
```

### Options inherited from parent commands

```
  -y, --yes   Assume yes for all user prompts
```

### SEE ALSO



#### Go Back to [CLI Commands](vela) Homepage.


###### Auto generated by spf13/cobra on 19-Apr-2022, refer to [script in KubeVela](https://github.com/oam-dev/kubevela/tree/master/hack/docgen).
