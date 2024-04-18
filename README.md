

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

## Release

- Increment the version in pyproject.toml according to the versioning scheme
- Draft a new release on GitHub
    - Use vMAJOR.MINOR.PATCH (e.g. v1.2.3) as both the tag and release title
      - The version should follow [semantic versioning](https://semver.org/) and [PEP 440](https://www.python.org/dev/peps/pep-0440/). 
    - Fill in the release description. You can use the "Generate release notes" function to get a draft for this
- Commit your changes and push to main
- Publish the release
- Go to Actions and approve the release workflow
- Check that the workflow runs successfully
