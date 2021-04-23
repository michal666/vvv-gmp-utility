# vvv-gmp-utility

Utility to install GMP as part of provisioning in [VVV](https://github.com/varying-vagrant-vagrants/vvv/).

## How To Use

Extend your `vvv-custom.yml` like this:

```yml
utilities:
  gmp:
    - gmp

utility-sources:
  gmp: https://github.com/michal666/vvv-gmp-utility
```

For more see the [official VVV documentation on utilities](https://varyingvagrantvagrants.org/docs/en-US/utilities/).

## Supported Versions

**GMP**

- `gmp`
