# DockerImageBuilder
Automatically build docker images using GitHub Action, tracing the repos regularly on schedule.
- [sharelatex-base](https://hub.docker.com/r/liuyujie99/sharelatex-base) 
  - Pulls: ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex-base)
  - Build schedule: 
    - Latest: Every time when `sharelatex.json` changes.
      - Status: [![sharelatex-latest](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-latest.yml/badge.svg)](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-latest.yml)
    - Nightly: Every day.
      - Status: [![sharelatex-nightly](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-nightly.yml/badge.svg)](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-nightly.yml)
  - Architecture: AMD64, ARM64

- [sharelatex](https://hub.docker.com/r/liuyujie99/sharelatex) 
  - Pulls: ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex)
  - Build Schedule: 
    - Latest: Every time when `sharelatex.json` changes.
      - Status: [![sharelatex-latest](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-latest.yml/badge.svg)](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-latest.yml)
    - Nightly: Every day
      - Status: [![sharelatex-nightly](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-nightly.yml/badge.svg)](https://github.com/ActionsTools/DockerImageBuilder/actions/workflows/sharelatex-nightly.yml)
  - Architecture: AMD64, ARM64