## minishift config view

Display values currently set in the minishift config file

### Synopsis


Display values currently set in the minishift  config file.

```
minishift config view
```

### Options

```
      --format string   Go template format string for the config view output.  The format for Go templates can be found here: https://golang.org/pkg/text/template/
For the list of accessible variables for the template, see the struct values here: https://godoc.org/github.com/jimmidyson/minishift/cmd/minikube/cmd/config#ConfigViewTemplate (default "- {{.ConfigKey}}: {{.ConfigValue}}\n")
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --log-flush-frequency duration     Maximum number of seconds between log flushes (default 5s)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory (default "")
      --logtostderr                      log to standard error instead of files
      --show-libmachine-logs             Whether or not to show logs from libmachine.
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [minishift config](minishift_config.md)	 - Modify minishift config
