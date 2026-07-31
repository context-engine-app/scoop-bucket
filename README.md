# Context Engine Scoop Bucket

Add the organization-owned bucket and install Context Engine:

```powershell
scoop bucket add context-engine https://github.com/context-engine-app/scoop-bucket
scoop install context-engine/context-engine
```

Update or uninstall it with:

```powershell
scoop update context-engine
scoop uninstall context-engine
```

The manifest installs the immutable, versioned Windows archive published by
[`context-engine-app/context-engine-mcp`](https://github.com/context-engine-app/context-engine-mcp/releases). It uses
only Scoop's declarative portable-application fields and runs no installer or pre/post-install script.
