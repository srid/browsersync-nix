[Browsersync](https://www.browsersync.io/) packaged up in Nix, so that you may [refrain](https://notes.srid.ca/nojs) from touching anything Javascript with a ten foot pole.

```
$(nix-build --no-out-link -A nodeDependencies)/bin/browser-sync
```
