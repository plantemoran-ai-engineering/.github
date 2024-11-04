# Default (root) GitHub project

[![Backup Repo][img--gh-action-badge--backup-repo]][gh-action--backup-repo]
[![Code Vulnerability Scanning][img-gh-action-cvs-badge]][gh-action-cvs]
[![HCL AppScan - SAST Scan][img--gh-action-badge--appscan-sast]][gh-action--appscan-sast]
[![Linting][img-gh-action-lint-badge]][gh-action-lint]

GitHub supports a repository (named `.github`) with files that are inherited by all other projects.
These "default" files will be used for any repository owned by the account that does not contain its own file of that type.

For more information, please see [Creating a default community health file][gh-creating-default-comm-health-file].

## Issue Templates

This repo contains 2 types of issue templates:

- markdown templates
- issue forms templates
  - NOTE: Issue forms are available in beta for public repositories on GitHub.com.
  - We have created form templates for when they become available for private repos.

### Included Templates

- Bug Report
  - This template will be used when creating bugs.
- Feature Request
  - This template will be used when requesting a new feature or enhancement.

## Organization Profile

This special repository also contains a special file `./profile/README.md` that will appear on the organizations profile.

<!-- reference urls -->

[gh-action--backup-repo]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/backup-repo.yml
[gh-action-cvs]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/code-analysis.yml
[gh-action-lint]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/linting.yml
[gh-creating-default-comm-health-file]: https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file
[gh-action--appscan-sast]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/hcl-appscan-sast-scan.yml
[img--gh-action-badge--backup-repo]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/backup-repo.yml/badge.svg
[img--gh-action-badge--appscan-sast]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/hcl-appscan-sast-scan.yml/badge.svg
[img-gh-action-cvs-badge]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/code-analysis.yml/badge.svg
[img-gh-action-lint-badge]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/linting.yml/badge.svg
