---
title: Tilt CLI Reference
layout: docs
hideEditButton: true
---
## tilt dump cli-docs

Dumps markdown docs of the CLI

### Synopsis

Dumps markdown docs of the CLI

```
tilt dump cli-docs [flags]
```

### Options

```
      --dir string   The directory to dump to (default ".")
  -h, --help         help for cli-docs
```

### Options inherited from parent commands

```
  -d, --debug                          Enable debug logging
      --klog int                       Enable Kubernetes API logging. Uses klog v-levels (0-4 are debug logs, 5-9 are tracing logs)
      --log-flush-frequency duration   Maximum number of seconds between log flushes (default 5s)
      --trace                          Enable tracing
      --traceBackend string            Which tracing backend to use. Valid values are: 'windmill', 'lightstep', 'jaeger' (default "windmill")
  -v, --verbose                        Enable verbose logging
```

### SEE ALSO

* [tilt dump](tilt_dump.html)	 - Dump internal Tilt state

###### Auto generated by spf13/cobra on 19-Jun-2020
