---
date: 2019-09-23T21:39:11Z
title: "jx get devpod"
slug: jx_get_devpod
url: /commands/jx_get_devpod/
---
## jx get devpod

Lists the DevPods

### Synopsis

Display the available DevPods 

For more documentation see: https://jenkins-x.io/developing/devpods/

```
jx get devpod [flags]
```

### Examples

```
  # List all the possible DevPods
  jx get devPod
```

### Options

```
      --all-usernames     Gets devpods for all usernames
  -h, --help              help for devpod
      --username string   The username to create the DevPod. If not specified defaults to the current operating system user or $USER'
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 23-Sep-2019