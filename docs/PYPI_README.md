# project-template

Template repository for packages belonging phantom-nms

Usage:

- Pick this template in GitHub.
- If you don't want to use the `src` folder, rename it and replace all references to `src` with the new target folder.
- Run `pre-commit install && pre-commit autoupdate`
- Update pyproject.toml with your dependencies and run `pdm update` to create a lock file.
- Update the project description, keywords, author, maintainers etc. in pyproject.toml

## Docs

> [!IMPORTANT]\
> TODO

## Sonar

- Import the repository into sonarcloud and update the sonar properties file to use the correct project key.
- Add the `SONAR_TOKEN` secret in GitHub as an action secret.

## Release

- To release you need to set the `PYPI_TOKEN` value in GitHub.
