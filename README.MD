# Vodyani Package Template

*This repository contains project templates that are widely used by the vodyani npm packge, and you may build templates by selecting various branches.*

## Branches

### JavaScript Common Package

**Usage:**

1. *Clone to local.*

```
git clone -b js https://github.com/vodyani/package.git <YOUR_PACKAGE_NAME>
```

2. *Modify the preset in package.json and replace the previous value with the name-package information you want to broadcast.*

- <PACKAGE_NAME>
- <PACKAGE_DESCRIPTION>

### TypeScript / Nest Common Package

**Usage:**

1. *Clone to local.*

```
git clone -b ts https://github.com/vodyani/package.git <YOUR_PACKAGE_NAME>
```

use nest template:

```
git clone -b nest https://github.com/vodyani/package.git <YOUR_PACKAGE_NAME>
```


2. *Modify the preset in package.json and replace the previous value with the name-package information you want to broadcast.*

- <PACKAGE_NAME>
- <PACKAGE_DESCRIPTION>

3. *Add Codecov token to vodyani organization secrets.*

[Actions secrets](https://github.com/organizations/vodyani/settings/secrets/actions)

create codecov token like:

```
CODECOV_CI_TOKEN_BY_<YOUR_PACKAGE_NAME>
```

4. *Replace github workflows secrets*

- <PACKAGE_CODE_COV_CI_TOKEN>

5. *Replace readme badge*

- <PACKAGE_CODE_COV_BADGE>


## License

Vodyani Package Template is [MIT licensed](LICENSE).