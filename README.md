# sigit Scoop bucket

A [Scoop](https://scoop.sh) bucket for **[siGit Code](https://sigit.si)** — an AI
coding agent that runs on your machine.

## Install

```powershell
scoop bucket add sigit https://github.com/getsigit/scoop-bucket
scoop install sigit
```

## Update

```powershell
scoop update sigit
```

## Uninstall

```powershell
scoop uninstall sigit
```

## About this bucket

The `bucket/sigit.json` manifest is generated and updated automatically by the
[`release-scoop.yml`](https://github.com/getsigit/sigit/blob/main/.github/workflows/release-scoop.yml)
workflow in the [`getsigit/sigit`](https://github.com/getsigit/sigit) repository
on every release. It points at the `sigit-win-amd64.exe` / `sigit-win-arm64.exe`
assets from the corresponding GitHub release and carries their SHA-256 checksums,
so please don't edit it by hand.
