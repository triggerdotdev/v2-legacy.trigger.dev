### trigger.dev v2 is now deprecated.

Please upgrade to v3. [Read the migration guide](https://trigger.dev/docs/guides/use-cases/upgrading-from-v2).

This repo contains v2 specific code:

- Integration packages
- v2 CLI
- Yalt package and server
- Framework adapter packages

[Discord](https://trigger.dev/discord) | [Website](https://trigger.dev) | [Issues](https://github.com/triggerdotdev/trigger.dev/issues) | [Docs](https://trigger.dev/docs)

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/triggerdotdev.svg?style=social&label=Follow%20%40trigger.dev)](https://twitter.com/triggerdotdev)

### Releasing a new patch version

```sh
pnpm run changeset:add
pnpm run changeset:version
git commit -am "chore: release 3.0.x"
git push
pnpm run changeset:release
```
