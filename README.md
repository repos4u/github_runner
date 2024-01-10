# Github runner with additional dependencies installed

This repository pulls the latest image from [myoung34/docker-github-actions-runner official repo](https://github.com/myoung34/docker-github-actions-runner) and installs additional dependencies into the Docker image.

### Get Sources

Access this Dockerfile either by directly downloading this repository from GitHub&reg;, or by cloning this repository and then navigating to the appropriate folder.
```bash
git clone https://github.com/repos4u/github_runner.git
cd github_runner
```

### Build the Docker Image

```bash
docker build -t github_runner:latest .
```