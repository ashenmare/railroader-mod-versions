# railroader-mod-versions

The list of latest versions that the Mod Updates mod for Railroader reads when you press its Check button. One file, `versions.json`, kept up to date when a mod is posted.

For each mod: its identifier (the one in its Info.json), display name, latest version on Nexus, Nexus page id, GitHub repo when it has one, and whether it is retired (with a one-line reason).

Schema 1:
```
{ "schema": 1, "generated": "YYYY-MM-DD",
  "mods": { "owner/name": { "name": "...", "version": "1.2.3" | null, "nexus": 1234 | null, "github": "owner/repo" | null,
                            "retired": false, "why": "(retired only)", "replacedBy": "(optional)" } } }
```
