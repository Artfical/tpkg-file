# file

file 5.46: tells what a file is, with its magic database

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install file
```

| | |
|---|---|
| Version | 5.46 |
| Licence | BSD-2-Clause |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 534338 bytes (10553144 unpacked) |
| SHA-256 of the `.tpkg` | `b34accccacefc5f29eb1b9dfcde163f1cc4850be0a475e5e655c66cfc85fa8bc` |

## Commands it adds

| Command | Runs |
|---|---|
| `file` | `bin/file` |

## Download

The package file (`file-5.46.tpkg`) and the sources it was built from are the assets of the
[v5.46 release](https://github.com/Artfical/tpkg-file/releases/tag/v5.46).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `file-5.46.tar.gz`

Check a download: `sha256sum file-5.46.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: BSD-2-Clause. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
