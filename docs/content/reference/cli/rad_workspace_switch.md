---
type: docs
date: 2023-08-15T23:32:25Z
title: "rad workspace switch CLI reference"
linkTitle: "rad workspace switch"
slug: rad_workspace_switch
url: /reference/cli/rad_workspace_switch/
description: "Details on the rad workspace switch Radius CLI command"
---
## rad workspace switch

Switch current workspace

### Synopsis

Switch current workspace

```
rad workspace switch [flags]
```

### Examples

```
# Switch current workspace
rad workspace switch my-workspace
```

### Options

```
  -h, --help               help for switch
  -w, --workspace string   The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
  -o, --output string   output format (supported formats are json, table) (default "table")
```

### SEE ALSO

* [rad workspace]({{< ref rad_workspace.md >}})	 - Manage workspaces

###### Auto generated by spf13/cobra on 15-Aug-2023