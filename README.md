# DMMHub — Community Directory

A curated directory of [DMM](https://github.com/nikube/DMM)-compatible Dolibarr modules.

## What is this?

This repository contains a `dmmhub.json` file that lists DMM-compatible Dolibarr modules. [DoliModuleManager (DMM)](https://github.com/nikube/DMM) can subscribe to this directory to discover, install and update modules in one click.

## How to use

This hub is pre-configured in DMM by default. If you need to add it manually:

1. Open DMM in Dolibarr → **Settings** tab
2. In the **Module Hubs** section, add this URL:
   ```
   https://raw.githubusercontent.com/nikube/DMMHub/master/dmmhub.json
   ```
3. Click **Add** — listed modules will be imported automatically

## Modules listed

| Module | Repository | Description |
|---|---|---|
| DoliModuleManager | [nikube/DMM](https://github.com/nikube/DMM) | Module manager with GitHub integration |
| SQL Magic | [nikube/sqlmagic](https://github.com/nikube/sqlmagic) | Parameterized SQL queries in self-service |
| Adminer for Dolibarr | [nikube/adminer4dolibarr](https://github.com/nikube/adminer4dolibarr) | Adminer database management integrated into Dolibarr |
| File Manager for Dolibarr | [nikube/filemanager4dolibarr](https://github.com/nikube/filemanager4dolibarr) | Web file manager integrated into Dolibarr |
| Object Banner | [nikube/objectbanner](https://github.com/nikube/objectbanner) | Floating navigation banner on document cards |

## Add your module

To list your module in this hub, submit a PR adding an entry to `dmmhub.json`:

```json
{
  "repo": "your-org/your-module",
  "public": true,
  "name": "Your Module Name",
  "description": "Short description"
}
```

Your module must have a `dmm.json` manifest at its root. See the [DMM specification](https://github.com/nikube/DMM/blob/master/DMM_SPECIFICATION.md) for details.

## License

MIT

## Author

Nicolas - [AnatoleConseil.com](https://anatoleconseil.com/) — nz@anatoleconseil.com
