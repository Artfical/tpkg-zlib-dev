# zlib-dev

zlib 1.3.1 headers and libraries (libz.a, libz.so) for building programs with gcc

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install zlib-dev
```

| | |
|---|---|
| Version | 1.3.1 |
| Licence | Zlib |
| Upstream | https://zlib.net |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`zlib`](https://github.com/Artfical/tpkg-zlib) |
| Needs tOS build | 615 or newer |
| Size | 214296 bytes (498957 unpacked) |
| SHA-256 of the `.tpkg` | `6b125513c121a5b2874cd63315ee5715ea78688c004141506986a65a372a39bb` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`zlib-dev-1.3.1.tpkg`) and the sources it was built from are the assets of the
[v1.3.1 release](https://github.com/Artfical/tpkg-zlib-dev/releases/tag/v1.3.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `zlib-1.3.1.tar.gz`

Check a download: `sha256sum zlib-dev-1.3.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Zlib. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
