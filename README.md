# Default (root) GitHub project

[![Backup Repo][img--gh-action-badge--backup-repo]][gh-action--backup-repo]
[![HCL AppScan - SAST Scan][img--gh-action-badge--appscan-sast]][gh-action--appscan-sast]
[![Linting][img--gh-action-badge--lint]][gh-action--lint]

GitHub supports a repository (named `.github`) with files that are inherited by all other projects.
These "default" files will be used for any repository owned by the account that does not contain its own file of that type.

For more information, please see [Creating a default community health file][gh-creating-default-comm-health-file].

## Getting Started

Ensure you have the following tools installed before getting started.

**NOTE:** Always be sure to use **_only_** approved versions from the [Developer Workstation Configuration][developer-workstation-config-docs] guide.

- Git
- NVM
- Node (20.x)
- VS Code
  - This includes all recommended VS Code extensions (included in /.vscode/extensions.json)
- Dependencies
  - `npm install`

## Scripts

The following scripts are available in this repository:

- `format:check`: run prettier and check if files are properly formatted
  - e.g. `npm run format:check`
  - NOTE: this will not change any files; it will notify you if any files need reformatting
- `format`: format code using prettier
  - e.g. `npm run format`
  - NOTE: this will **make changes** to files
  - NOTE: it is recommended to run this when there are no pending changes on the branch
    - this way, you can see all changes made by prettier
- `lint`: lint code (markdown)
  - e.g. `npm run lint`

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

## Contributing

To contribute to this repository, please see the [contribution guidelines](CONTRIBUTING.md).

<!-- reference urls -->

[developer-workstation-config-docs]: https://plantemoran-appdev.github.io/github-process-docs/workstation-setup/workstation-config/
[gh-action--appscan-sast]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/hcl-appscan-sast-scan.yml
[gh-action--backup-repo]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/backup-repo.yml
[gh-action--lint]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/linting.yml
[gh-creating-default-comm-health-file]: https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file
[img--gh-action-badge--appscan-sast]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/hcl-appscan-sast-scan.yml/badge.svg
[img--gh-action-badge--backup-repo]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/backup-repo.yml/badge.svg
[img--gh-action-badge--lint]: https://github.com/plantemoran-ai-engineering/.github/actions/workflows/linting.yml/badge.svg
