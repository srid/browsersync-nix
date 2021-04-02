[Browsersync](https://www.browsersync.io/) packaged up in Nix, so you can refrain from touching JS with a ten foot pole.

```
$(nix-build --no-out-link -A nodeDependencies)/bin/browser-sync
```
