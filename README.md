# release-radar-smoke

Smoke-test репо для [spatially-release-radar](https://github.com/ivmakar/spatially-release-radar).
Каждый push в `develop` триггерит `deploy-marker.yml` → workflow_run → webhook → `/ingest/github` на VPS.

Удаляется после прохождения e2e-smoke task.
