# hls-indexer-chart

Helm chart for [hls-indexer](https://github.com/vmorshc/hls-indexer): api, worker and Redis.

`image.tag` in `charts/hls-indexer/values.yaml` is a template (`latest`). The GitHub Actions workflow of the application repository writes the released version there; Argo CD syncs the change.

```bash
helm template hls-indexer charts/hls-indexer
```
