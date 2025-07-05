| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/android/android-original.svg" width="50" /> | ANDROID APP TEMPLATE |
| --------------------------------------------------------------------------------------------------------------- | -------------------- |

![main GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/sripwoud/android-template/main.yml?branch=main&label=main)

| Feature                                                                                                               | With                                                                                         | Configuration File                                     |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Build                                                                                                                 | [expo](https://expo.dev)                                                                     | [app.config.json](./app.config.js)                     |
| Continuous Integration                                                                                                | [github workflow](https://docs.github.com/en/actions/using-workflows)                        | [.github/workflows](./.github/workflows)               |
| Conventional Commits (`main` branch only)                                                                             | [convco](https://github.com/convco/convco)                                                   | [.convco](./.convco)                                   |
| Conventional PR Titles (because I only squash merge and base changelogs/semantic versioning on `main` commit history) | [amann/action-semantic-pull-request](https://github.com/amannn/action-semantic-pull-request) | [semantic-pr.yml](./.github/workflows/semantic-pr.yml) |
| Git Hooks                                                                                                             | [hk](https://hk.jdx.dev/)                                                                    | [hk.pkl](./hk.pkl)                                     |
| Formatting                                                                                                            | [dprint](https://dprint.dev/)                                                                | [.dprint.jsonc](./.biome.json)                         |
| Form                                                                                                                  | [@tanstack/react-form](https://tanstack.com/form/latest)                                     |                                                        |
| Import Aliases                                                                                                        | [typescript paths](https://www.typescriptlang.org/tsconfig#paths)                            | [tsconfig.json](./tsconfig.json)                       |
| Linting                                                                                                               | [biome](https://biomejs.dev/)                                                                | [.biome.jsonc](./.biome.jsonc)                         |
| Tasks Runner, Environment & Runtime Management                                                                        | [mise](https://mise.dev/)                                                                    | [mise.toml](./mise.toml)                               |
| Typings                                                                                                               | [typescript](https://www.typescriptlang.org/)                                                | [tsconfig.json](./tsconfig.json)                       |

## Develop

I use [`mise`](https://mise.jdx.dev) to manage runtimes, manage environment variables, and run tasks.\
To install it and setup the repository:

```commandline
./setup
```

To run tasks interactively:

```commandline
mise run
```
