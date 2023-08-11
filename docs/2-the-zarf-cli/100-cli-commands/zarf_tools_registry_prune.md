# zarf tools registry prune
<!-- Auto-generated by hack/gen-cli-docs.sh -->

Prunes images from the registry that are not currently being used by any Zarf packages.

```
zarf tools registry prune [flags]
```

## Options

```
      --confirm   Confirm the image prune action to prevent accidental deletions
  -h, --help      help for prune
```

## Options inherited from parent commands

```
      --allow-nondistributable-artifacts   Allow pushing non-distributable (foreign) layers
      --insecure                           Allow image references to be fetched without TLS
      --platform string                    Specifies the platform in the form os/arch[/variant][:osversion] (e.g. linux/amd64). (default "all")
  -v, --verbose                            Enable debug logs
```

## SEE ALSO

* [zarf tools registry](zarf_tools_registry.md)	 - Tools for working with container registries using go-containertools