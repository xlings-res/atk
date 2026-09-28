# atk

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/a/atk.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/atk-1.0-2.38.0-h04ea711_2.conda | `df682395d05050cd1222740a42a551281210726a67447e5258968dd55854302e` | conda-forge atk-1.0 2.38.0 h04ea711_2 (LGPL-2.0-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name atk \
    --version 2.38.0 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/atk-1.0-2.38.0-h04ea711_2.conda#df682395d05050cd1222740a42a551281210726a67447e5258968dd55854302e \
    --require lib/libatk-1.0.so.0
```

