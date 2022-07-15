[![tests](https://github.com/mandrasch/ddev-deployer-dep/actions/workflows/tests.yml/badge.svg)](https://github.com/mandrasch/ddev-deployer-dep/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2022.svg)

Work in progress, DDEV addon for Deployer `dep`-command.

Install via

```bash
ddev get mandrasch/ddev-addon-deployer-dep
```

Usage after installation: `ddev dep <your-command>`

Deployer must be installed via `ddev composer require --dev deployer/deployer:^7`, otherwise this won't work.

All it does is adding this custom command file to `.ddev/`:

https://github.com/mandrasch/ddev-deployer-dep/blob/main/commands/web/dep

Created via https://github.com/drud/ddev-addon-template
