# scoop-bucket

Scoop bucket for docodego — the intent-and-evidence layer for the agent age.

```sh
scoop bucket add docodego https://github.com/DoCoDeGo/scoop-bucket
scoop install docodego
```

Manifests track GitHub releases automatically (`checkver: github`); every
update's hash is read from the release's own `sha256sums.txt`, so Scoop
verifies against the same sums the release ships.
