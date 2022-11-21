# DockerImageBuilder
Automatically build docker images using GitHub Action, tracing the repos regularly on schedule.  
To limit the usage of free GitHub Actions, the minimal build interval in this project will be one week.
- [sharelatex-base](https://hub.docker.com/r/liuyujie99/sharelatex-base) 
  - Status:
  ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex-base)
  ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex-base)
  - Schedule: the first day of every month
  - Architecture: AMD64, ARM64
- [sharelatex](https://hub.docker.com/r/liuyujie99/sharelatex) 
  - Status:
  ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ActionsTools/DockerImageBuilder/sharelatex)
  ![Docker Pulls](https://img.shields.io/docker/pulls/liuyujie99/sharelatex)
  - Schedule: the first day of every month, after `sharelatex-base` is built.
  - Architecture: AMD64, ARM64

