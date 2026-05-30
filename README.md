# Setup tox test environments

Find all tox environments configured by "type"

## Example Usage

```
  setup:
    uses: infrabits/ci-setup-tox-env/.github/workflows/setup.yml@main
```

or

```
    steps:
      - uses: infrabits/ci-setup-tox-envs@main
        id: tox_envs
```
