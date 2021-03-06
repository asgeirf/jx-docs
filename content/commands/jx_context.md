---
date: 2018-04-16T18:22:39Z
title: "jx context"
slug: jx_context
url: /commands/jx_context/
---
## jx context

View or change the current kubernetes context (kubernetes cluster)

### Synopsis

Displays or changes the current kubernetes context (cluster).

```
jx context [flags]
```

### Examples

```
  # to select the context to switch to
  jx context
  
  # or the more concise alias
  jx ctx
  
  # view the current context
  jx ctx -b
  
  # Change the current namespace to 'minikube'
  jx ctx minikube
```

### Options

```
  -b, --batch-mode   In batch mode the command never prompts for user input
      --headless     Enable headless operation if using browser automation
  -h, --help         help for context
      --no-brew      Disables the use of brew on MacOS to install or upgrade command line dependencies
      --verbose      Enable verbose logging
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 16-Apr-2018
