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

Manifests live at the repository root. Each manifest is published from that project's release workflow. The peaproxy manifest tracks the current GitHub release.

## License

MIT. See [LICENSE](LICENSE).
