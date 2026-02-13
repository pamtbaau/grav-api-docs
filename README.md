# Template for phpDocumentor generating Grav API docs

Based on fork of [phpDocumentor-markdown](https://github.com/Saggre/phpDocumentor-markdown)

Use case: Generate markdown page for Grav API documentation

## Installation & Usage
- Please refer to [this guide](https://docs.phpdoc.org/guide/getting-started/installing.html) for instructions on installing phpDocumentor.
- Drop `phpDocumentor` into root of repo and rename to `phpdoc`
- Usage instructions assume that `phpdoc` is the phpDocumentor binary.
- Update `phpdoc.dist.xml`:
  - to point `source` to `system/src/Grav` in Grav installation
  - to set path to where `default.md` will be created

### Running manually
```bash
# Run phpDocumentor inside root folder of repo. It will pick up definition in `phpdoc.dist.xml`
$ phpdoc
```

## Thanks to [Sakri Koskimies](https://github.com/Saggre)