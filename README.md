# DockerImageBuilder
Automatically build docker images using GitHub Action, tracing the repos regularly on schedule.  
To limit the usage of free GitHub Actions, the minimal build interval in this project will be one week.
- [sharelatex-base](https://hub.docker.com/r/liuyujie99/sharelatex-base) 
  - Pulls: ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex-base)
  - Build schedule: 
    - Latest: Every time when `sharelatex.json` changes.
      - Status: ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex-latest)
    - Nightly: Every Monday.
      - Status: ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex-nightly)
  - Architecture: AMD64, ARM64

- [sharelatex](https://hub.docker.com/r/liuyujie99/sharelatex) 
  - Pulls: ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex)
  - Build Schedule: 
    - Latest: Every time when `sharelatex.json` changes.
      - Status: ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex-latest)
    - Nightly: Every Monday
      - Status: ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex-nightly)
  - Architecture: AMD64, ARM64

