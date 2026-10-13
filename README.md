# ks1686/scoop-bucket

Self-hosted [Scoop](https://scoop.sh) bucket for [genv](https://github.com/ks1686/genv) and [peaproxy](https://github.com/ks1686/peaproxy).
Not submitted to Scoop extras or the scoop.sh directory.

## Install

```powershell
scoop bucket add ks1686 https://github.com/ks1686/scoop-bucket
scoop install genv
scoop install peaproxy
```

- **genv** — cross-platform environment manager
- **peaproxy** — localhost AI gateway (API keys and optional subscription OAuth)

Manifests live at the repository root and are written by GoReleaser from each project's release workflow, so fixes belong in [ks1686/genv](https://github.com/ks1686/genv) or [ks1686/peaproxy](https://github.com/ks1686/peaproxy).

The [validate](.github/workflows/validate.yml) workflow runs on every push, pull request, and weekly on Windows: it validates each manifest against Scoop's JSON schema, then runs `scoop install` from this checkout (verifying the hash) and checks `--version`.

## License

MIT. See [LICENSE](LICENSE).
