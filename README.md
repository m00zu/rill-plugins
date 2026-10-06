# Rill plugins

Released plugin versions for [Rill](https://github.com/m00zu), a workflow app for scientific data.

This repository holds only what Rill downloads: `index.json` and one Release per plugin
version (tag `<id>-v<version>`, asset `<id>-<version>.rillp`). Rill reads the index to offer
updates in its Plugins tab; a saved node keeps its version line (for example 1.2) and runs the
newest fix of it. The source lives elsewhere and is private; the packages here are public.

Each version in `index.json` names its download, SHA-256 and size (Rill refuses a download
that does not match), its release notes, the plugin SDK and oldest Rill it needs, and the
other plugins it needs.

Versions are published with `rill plugin publish` from the author's machine.
