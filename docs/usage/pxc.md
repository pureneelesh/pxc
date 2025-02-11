## pxc

Portworx client

### Synopsis

pxc is a Portworx client which allows users to communicate with their storage cluster
from their client machine combining information from both Kubernetes and Portworx.

Please see https://docs.portworx.com/reference/ for more information.

```
pxc [flags]
```

### Options

```
  -h, --help                    help for pxc
      --options                 Show global options for all commands
      --pxc.config string       Config file (default is $HOME/.pxc/config.yml)
      --pxc.config-dir string   Config directory (default "/home2/lpabon/.pxc")
      --pxc.context string      Force context name for the command
      --pxc.token string        Portworx authentication token
      --pxc.v int32             [0-3] Log level verbosity
```

### SEE ALSO

* [pxc auth](pxc_auth.md)	 - Manage Portworx authentication
* [pxc cluster](pxc_cluster.md)	 - Manage Portworx cluster
* [pxc component](pxc_component.md)	 - Configure components
* [pxc config](pxc_config.md)	 - Setup pxc configuration
* [pxc context](pxc_context.md)	 - Manage connections to Portworx and other systems
* [pxc node](pxc_node.md)	 - Portworx node management
* [pxc script](pxc_script.md)	 - Run a script against the current cluster
* [pxc utilities](pxc_utilities.md)	 - pxc utility commands
* [pxc version](pxc_version.md)	 - Show pxc version information
* [pxc volume](pxc_volume.md)	 - Volume life cycle management

###### Auto generated by spf13/cobra on 24-Mar-2021
