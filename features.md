## Genernal
- PEP 582 local package directory
- **No virtualenv**
- PEP 517 builds
- Plugins system like docker CLI.
- Project template tool as a optional plugin.

## Dependencies specification
- Multiple requirements of a package
- Option to exclude one package
- Multiple dependency sections beyond `default` and `dev`
- Extras defined in dependency sections
- Python specifiers merging
- Editable requirements support

## Dependencies resolution
- Package metadata cache
- Clever hash resolving

## `pdm add`
- Option to add packages to given section
- Option to save package version as pinned, minimum or wildcard
- Option to perform installation(for default and dev) or not(for other sections)

## `pdm install`
- Option to install specific section
- Option to not install default dependencies
