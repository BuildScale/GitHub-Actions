# GitHub Actions

[![GitHub stars](https://img.shields.io/github/stars/BuildScale/GitHub-Actions?logo=github)](https://github.com/BuildScale/GitHub-Actions/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/BuildScale/GitHub-Actions?logo=github)](https://github.com/BuildScale/GitHub-Actions/network)
[![Lines of Code](https://img.shields.io/badge/lines%20of%20code-6.5k-lightgrey?logo=codecademy)](https://github.com/BuildScale/GitHub-Actions)
[![License](https://img.shields.io/github/license/BuildScale/GitHub-Actions)](https://github.com/BuildScale/GitHub-Actions/blob/master/LICENSE)
[![My LinkedIn](https://img.shields.io/badge/LinkedIn%20Profile-BuildScale-blue?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIGZpbGw9IiNmZmZmZmYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPgo=)](https://www.linkedin.com/company/khulnasoft/)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/BuildScale/GitHub-Actions?logo=github)](https://github.com/BuildScale/GitHub-Actions/commits/master)

[![CI Builds Overview](https://img.shields.io/badge/CI%20Builds-Overview%20Page-blue?logo=circleci)](https://buildscale.github.io/CI-CD/)
[![YAML](https://github.com/BuildScale/GitHub-Actions/actions/workflows/yaml.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/yaml.yaml)
[![Markdown Lint](https://github.com/BuildScale/GitHub-Actions/actions/workflows/markdown.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/markdown.yaml)
[![Validation](https://github.com/BuildScale/GitHub-Actions/actions/workflows/validate.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/validate.yaml)
[![Grype](https://github.com/BuildScale/GitHub-Actions/actions/workflows/grype.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/grype.yaml)
[![Kics](https://github.com/BuildScale/GitHub-Actions/actions/workflows/kics.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/kics.yaml)
[![Semgrep](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep.yaml)
[![Semgrep Cloud](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep-cloud.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep-cloud.yaml)
[![URL Links](https://github.com/BuildScale/GitHub-Actions/actions/workflows/url_links.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/url_links.yaml)
[![Trivy](https://github.com/BuildScale/GitHub-Actions/actions/workflows/trivy.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/trivy.yaml)

[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-2088FF?logo=github)](https://github.com/BuildScale/GitHub-Actions)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-FCA121?logo=gitlab)](https://gitlab.com/BuildScale/GitHub-Actions)
[![Repo on Azure DevOps](https://img.shields.io/badge/repo-Azure%20DevOps-0078D7?logo=azure%20devops)](https://dev.azure.com/buildscale/GitHub/_git/GitHub-Actions)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-0052CC?logo=bitbucket)](https://bitbucket.org/BuildScale/GitHub-Actions)

GitHub Actions master template & GitHub Actions Reusable Workflows library.

- [main.yaml](https://github.com/BuildScale/GitHub-Actions/blob/master/main.yaml) - GitHub Actions master workflow template
- [.github/workflows/](https://github.com/BuildScale/GitHub-Actions/tree/master/.github/workflows) - GitHub Actions Reusable Workflows Library

See [Documentation](https://docs.github.com/en/actions/using-workflows/reusing-workflows#calling-a-reusable-workflow) for how to call these workflows directly from your own GitHub Actions workflow.

Fork this repo to have full control over all updates via Pull Requests. Create environment branches to stage updates across dev/staging/production.

Forked from [BuildScale/Templates](https://github.com/BuildScale/Templates), for which this is now a submodule.

To see GitHub Contexts available, including undocumented fields, see [BuildScale/GitHub-Actions-Contexts](https://github.com/BuildScale/GitHub-Actions-Contexts).

## Examples

In your GitHub repo, import these workflows by adding small yaml files to the `.github/workflows/` directory.

## Scan for Secrets and Security issues

[![Semgrep](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep.yaml)
Alerts appear under the GitHub repo's Security tab -> Code scanning alerts.

[![Semgrep Cloud](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep-cloud.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/semgrep-cloud.yaml) Alerts appear in the <https://semgrep.dev> dashboard

Create `.github/workflows/semgrep.yaml` for local repo alerts:

```yaml
on: [push]
jobs:
  semgrep:
    uses: BuildScale/GitHub-Actions/.github/workflows/semgrep.yaml@master
```

or `.github/workflows/semgrep-cloud.yaml` for <https://semgrep.dev> alerts:

```yaml
on: [push]
jobs:
  semgrep:
    uses: BuildScale/GitHub-Actions/.github/workflows/semgrep-cloud.yaml@master
    secrets:
      SEMGREP_APP_TOKEN: ${{ secrets.SEMGREP_APP_TOKEN }}
```

## Analyze your Terraform code security & best practices

[![tfsec](https://github.com/BuildScale/Terraform/actions/workflows/tfsec.yaml/badge.svg)](https://github.com/BuildScale/Terraform/actions/workflows/tfsec.yaml)
Alerts appear under Security -> Code scanning alerts.

Create `.github/workflows/tfsec.yaml`:

```yaml
on: [push]
jobs:
  tfsec:
    uses: BuildScale/GitHub-Actions/.github/workflows/tfsec.yaml@master
```

## Terraform Plan & Apply

Plans - updates Pull Requests with the results of validation, format check and full Change Plan outputs

Apply - applies when merged to default branch, eg. `master` or `main`

```yaml
on: [push, pull_request]
jobs:
  terraform:
    uses: BuildScale/GitHub-Actions/.github/workflows/terraform.yaml@master
    with:
      dir: path/to/terraform/code
    secrets:
      ...
```

For more sophisticated examples including approvals, secrets, branch and path selection etc. see my [Terraform repo](https://github.com/BuildScale/Terraform)'s templates for [terraform-plan.yaml](https://github.com/BuildScale/Terraform/blob/master/.github/workflows/terraform-plan.yaml.template) and [terraform-apply.yaml](https://github.com/BuildScale/Terraform/blob/master/.github/workflows/terraform-apply.yaml.template)

## Docker Build and push to DockerHub

[![Docker Build DevOps Bash Tools (Ubuntu)](https://github.com/BuildScale/Dockerfiles/actions/workflows/docker_build_devops_bash_tools_ubuntu.yaml/badge.svg)](https://github.com/BuildScale/Dockerfiles/actions/workflows/docker_build_devops_bash_tools_ubuntu.yaml)

Create `.github/workflows/dockerhub_build.yaml`:

```yaml
on: [push]
jobs:
  docker_build:
    uses: BuildScale/GitHub-Actions/.github/workflows/dockerhub_build.yaml@master
    with:
      repo: user/repo  # your DockerHub user/repo
      tags: latest v1.1
    secrets:
      DOCKERHUB_USER: ${{ secrets.DOCKERHUB_USER }}
      DOCKERHUB_TOKEN: ${{ secrets.DOCKERHUB_TOKEN }}
```

## Docker Build and push to AWS ECR

Create `.github/workflows/docker_build_aws_ecr.yaml`:

```yaml
on: [push]
jobs:
  docker_build:
    uses: BuildScale/GitHub-Actions/.github/workflows/docker_build_aws_ecr.yaml@master
    with:
      repo: MY_ECR_REPO
    secrets:
      AWS_ACCESS_KEY_ID: ${{ secrets.AWS_ACCESS_KEY_ID }}
      AWS_SECRET_ACCESS_KEY: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
      AWS_DEFAULT_REGION: ${{ secrets.AWS_DEFAULT_REGION }}
```

Creates several useful tags, supports multi-stage build caching, see [README](https://github.com/BuildScale/GitHub-Actions/blob/master/.github/workflows/README.md) for details.

## Check for Broken URL Links

[![URL Links](https://github.com/BuildScale/GitHub-Actions/actions/workflows/url_links.yaml/badge.svg)](https://github.com/BuildScale/GitHub-Actions/actions/workflows/url_links.yaml)

Create `.github/workflows/url_links.yaml`:

```yaml
on: [push]
jobs:
  url_links:
    uses: BuildScale/GitHub-Actions/.github/workflows/url_links.yaml@master
```

See [README](https://github.com/BuildScale/GitHub-Actions/blob/master/.github/workflows/README.md) for details on ignoring inaccessible / partially constructed links or those containing variables

## Auto-Merge Production hotfixes back to Staging

Merges via a Pull Request for full auditing.

Create `.github/workflows/merge_production_to_staging.yaml`:

```yaml
on: [push]
jobs:
  merge:
    if: github.ref_name == 'production'
    uses: BuildScale/GitHub-Actions/.github/workflows/merge-branch.yaml@master
    with:
      head: production  # from
      base: staging     # to
```

## Mirror Repos to GitLab for DR Backups

Mirrors all/given GitHub repos to GitLab - including all branches and tags, and GitHub repo description

```yaml
on:
  schedule:
    # mirror to GitLab hourly
    - cron: '0 0 * * *'

jobs:
  gitlab_mirror:
    uses: BuildScale/GitHub-Actions/.github/workflows/gitlab-mirror.yaml@master
    with:
      #organization: my-org    # optional: mirror your company's repos instead of your personal repos
      #repos: repo1 repo2 ...  # list of repos to mirror, space separated, rather than all repos
    secrets:
      GH_TOKEN: ${{ secrets.GH_TOKEN }}
      GITLAB_TOKEN: ${{ secrets.GITLAB_TOKEN }}
```

## AWS CodeArtifact - Publish a Python Package

```yaml
on:
  tags:
    - v*

jobs:
  aws_codeartifact_python_publish:
    uses: BuildScale/GitHub-Actions/.github/workflows/codeartifact_python_publish.yaml@master
    with:
      domain: mycompany     # your AWS CodeArtifact service domain name
      repo: mycompany-core  # your CodeArtifact repo name
      #command: make publish_package  # default. Can be any command using CODEARTIFACT_AUTH_TOKEN and CODEARTIFACT_REPO_URL
    secrets:
      AWS_ACCESS_KEY_ID: ${{ secrets.AWS_ACCESS_KEY_ID }}
      AWS_SECRET_ACCESS_KEY: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
      AWS_DEFAULT_REGION: ${{ secrets.AWS_DEFAULT_REGION }}
```

## Production

### Option 1 - Hashref

Import the reusable workflows from this repo as shown above, replacing `@master` with `@<hashref>` to fix to an immutable version (tags are not immutable). This is [GitHub Actions Security Best Practice](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#using-third-party-actions).

### Option 2 - Public Fork (fully automated)

Fork this repo for more control and visibility over all updates.

Enable the [fork-sync](https://github.com/BuildScale/GitHub-Actions/blob/master/.github/workflows/fork-sync.yaml) github actions workflow in your fork to keep the master branch sync'd every few hours.

You can then create tags or environment branches in your forked repo to stage updates across dev/staging/production.

If using environment branches enable the [fork-update-pr](https://github.com/BuildScale/GitHub-Actions/blob/master/.github/workflows/fork-update-pr.yaml) github actions workflow to automatically raise GitHub Pull Requests from master to your environment branches to audit, authorize & control updates.

### Option 3 - Private Copy (manual)

Copy `.github/workflows` to a private repo. Not recommended as it's the most manual legacy approach.

You will be responsible for committing and reconciling any divergences in your local copies.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=BuildScale/GitHub-Actions&type=Date)](https://star-history.com/#BuildScale/GitHub-Actions&Date)

## More Core Repos

<!-- OTHER_REPOS_START -->

### Knowledge

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Knowledge-Base&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Knowledge-Base)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Diagrams-as-Code&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Diagrams-as-Code)

<!--

Not support on GitHub Markdown:

<iframe src="https://raw.githubusercontent.com/BuildScale/BuildScale/main/knowledge.md" width="100%" height="500px"></iframe>

Does nothing:

<embed src="https://raw.githubusercontent.com/BuildScale/BuildScale/main/knowledge.md" width="100%" height="500px" />

-->

### DevOps Code

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=DevOps-Scripts&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/DevOps-Scripts)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=DevOps-Python-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/DevOps-Python-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=DevOps-Perl-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/DevOps-Perl-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=DevOps-Golang-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/DevOps-Golang-tools)

<!--
[![Gist Card](https://github-readme-stats.vercel.app/api/gist?id=f8f551332440f1ca8897ff010e363e03)](https://gist.github.com/BuildScale/f8f551332440f1ca8897ff010e363e03)
-->

### Containerization

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Kubernetes-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Kubernetes-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Dockerfiles&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Dockerfiles)

### CI/CD

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=GitHub-Actions&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/GitHub-Actions)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Jenkins&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Jenkins)

### DBA - SQL

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=SQL-scripts&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/SQL-scripts)

### DevOps Reloaded

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Nagios-Plugins&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Nagios-Plugins)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=HAProxy-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/HAProxy-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Terraform&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Terraform)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Packer-templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Packer-templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Nagios-Plugin-Kafka&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Nagios-Plugin-Kafka)

### Templates

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Template-repo&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Template-repo)

### Misc

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Spotify-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Spotify-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BuildScale&repo=Spotify-playlists&theme=ambient_gradient&description_lines_count=3)](https://github.com/BuildScale/Spotify-playlists)

The rest of my original source repos are
[here](https://github.com/BuildScale?tab=repositories&q=&type=source&language=&sort=stargazers).

Pre-built Docker images are available on my [DockerHub](https://hub.docker.com/u/buildscale/).

<!-- 1x1 pixel counter to record hits -->
![](https://hit.yhype.me/github/profile?user_id=2211051)

<!-- OTHER_REPOS_END -->
