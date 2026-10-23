# Scoop bucket of wolfpack

[wolfpack](https://github.com/realfamousbae/wolfpack) is a statically typed language whose
compiler, `wolf`, translates programs into readable TypeScript, Go and Rust.

```powershell
scoop bucket add wolfpack https://github.com/realfamousbae/scoop-wolfpack
```

```powershell
scoop install wolfpack
```

`scoop update wolfpack` updates it. `wolf run --vm` runs programs without other tools; `wolf setup`
installs Node.js, TypeScript, Go and Rust for the targets.

`bucket/wolfpack.json` is written by `release/scoop/manifest.sh` of the wolfpack repository: its
workflow `packages.yml` updates it when a release is published. Change the script there, not the
manifest here.
