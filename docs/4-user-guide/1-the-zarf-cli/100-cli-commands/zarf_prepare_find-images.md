## zarf prepare find-images

Evaluates components in a zarf file to identify images specified in their helm charts and manifests

### Synopsis

Evaluates components in a zarf file to identify images specified in their helm charts and manifests.

Components that have repos that host helm charts can be processed by providing the --repo-chart-path.

```
zarf prepare find-images [flags]
```

### Options

```
  -h, --help                     help for find-images
  -p, --repo-chart-path string   If git repos hold helm charts, often found with gitops tools, specify the chart path, e.g. "/" or "/chart"
      --set stringToString       Specify package variables to set on the command line (KEY=value) (default [])
      --tmpdir string            Specify the temporary directory to use for intermediate files
```

### Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc.
```

### SEE ALSO

* [zarf prepare](zarf_prepare.md)	 - Tools to help prepare assets for packaging

