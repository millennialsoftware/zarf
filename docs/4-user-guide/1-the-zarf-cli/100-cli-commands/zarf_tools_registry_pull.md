## zarf tools registry pull

Pull remote images by reference and store their contents locally

```
zarf tools registry pull IMAGE TARBALL [flags]
```

### Options

```
      --annotate-ref        Preserves image reference used to pull as an annotation when used with --format=oci
  -c, --cache_path string   Path to cache image layers
      --format string       Format in which to save images ("tarball", "legacy", or "oci") (default "tarball")
  -h, --help                help for pull
```

### Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc.
```

### SEE ALSO

* [zarf tools registry](zarf_tools_registry.md)	 - Collection of registry commands provided by Crane

