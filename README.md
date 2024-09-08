# github-actions-example-create-pull-request

## setup

- Repository settings
  - Access `Settings > Actions > General` and check `Allow GitHub Actions to create and approve pull requests`
  - ref: https://github.com/peter-evans/create-pull-request/issues/2767#issuecomment-1953810837
- GitHub Actions permissions
  - Give below permissions (Probably a substitute for `Read and write permissions` repository settings)

```yaml
permissions:
  contents: write
  pull-requests: write
```
