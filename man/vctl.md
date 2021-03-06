## vctl

vctl - A CLI tool for the container engine powered by VMware Fusion

### Synopsis

vctl Highlights:
• Build and run OCI containers.
• Push and pull container images between remote registries & local storage.
• Use a lightweight virtual machine (CRX VM) based on VMware Photon OS to host a container. Use 'vctl system config -h' to learn more.
• Easy shell access into virtual machine that hosts container. See 'vctl execvm’.

### Options

```
  -h, --help   Help for vctl
```

### SEE ALSO

* [vctl build](vctl_build.md)	 - Build a container image from a Dockerfile.
* [vctl create](vctl_create.md)	 - Create a new container from a container image.
* [vctl describe](vctl_describe.md)	 - Show details of a container.
* [vctl exec](vctl_exec.md)	 - Execute a command within a running container.
* [vctl execvm](vctl_execvm.md)	 - Execute a command within a running virtual machine that hosts container.
* [vctl images](vctl_images.md)	 - List container images.
* [vctl inspect](vctl_inspect.md)	 - Return low-level information on objects.
* [vctl kind](vctl_kind.md)	 - Get system environment ready for vctl-based KIND.
* [vctl login](vctl_login.md)	 - Log in to a registry.
* [vctl logout](vctl_logout.md)	 - Log out from a registry.
* [vctl ps](vctl_ps.md)	 - List containers.
* [vctl pull](vctl_pull.md)	 - Pull a container image from a registry.
* [vctl push](vctl_push.md)	 - Push a container image to a registry.
* [vctl rm](vctl_rm.md)	 - Remove one or more containers.
* [vctl rmi](vctl_rmi.md)	 - Remove one or more container images.
* [vctl run](vctl_run.md)	 - Run a new container from a container image.
* [vctl start](vctl_start.md)	 - Start an existing container.
* [vctl stop](vctl_stop.md)	 - Stop a container.
* [vctl system](vctl_system.md)	 - Manage the container engine.
* [vctl tag](vctl_tag.md)	 - Tag container images.
* [vctl version](vctl_version.md)	 - Print the version of vctl.
* [vctl volume](vctl_volume.md)	 - Manage volumes.

###### Auto generated by spf13/cobra on 14-Sep-2020
