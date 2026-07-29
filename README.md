# Context Engine Scoop Bucket

This public bucket is prepared for Context Engine but is not active yet. The manifest will be added only after the
immutable Windows release archive exists and passes native Windows validation.

After activation, add the organization-owned bucket and install Context Engine:

```powershell
scoop bucket add context-engine https://github.com/context-engine-app/scoop-bucket
scoop install context-engine/context-engine
```

Update or uninstall Context Engine with:

```powershell
scoop update context-engine
scoop uninstall context-engine
```

The manifest will install the immutable, versioned Windows archive published by
[`context-engine-app/context-engine-mcp`](https://github.com/context-engine-app/context-engine-mcp/releases). It uses
only Scoop's declarative portable-application fields and runs no installer or pre/post-install script.
