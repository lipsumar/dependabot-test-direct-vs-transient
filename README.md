# dependabot-test

This repository is used to test the config of dependabot.

This repo includes only transient dependencies of `dependabot-test`, but this time they are direct dependencies.

## Packages

### Direct dependencies

#### `loader-utils`

- spec `^0.2.16`
- yarn lock resolves to: `0.2.17`
  - has vulnerability, fixed in `1.4.1`

> Dependabot PR
>
> - update spec to `^1.4.2` (latest patch of 1.x)
> - update lock to resolve to `1.4.2`

#### `cross-spawn`

- spec `^7.0.3`
- yarn lock resolves to `7.0.3`
  - has vulnerability, fixed in `7.0.5`
- latest `7.0.6`

> Dependabot PR
>
> - update spec to `^7.0.5`
> - update lock to resolve to `7.0.5`
