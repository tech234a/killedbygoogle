<div align="center">
  <img src="../src/assets/tombstone.png" alt="tombstone" style="height: 80px; width: 80px; padding: 0 20px;">
  <h1>Killed by Google</h1>
  <p>A tribute and log of beloved products and services killed by Google.</p>
</div>

## Contributing Guide

### Pull Request

If you are contributing any code outside of `graveyard.json`, please ensure that your Pull Request will pass continuous integration. Run `yarn test` before opening your pull request which will check the React/Jest tests as well as verify `graveyard.json` is formatted correctly. These tests are extremely important to quickly merging pull requests for this project.

#### Continuous Integration
Killed by Google is using [GitHub Actions](https://github.com/features/actions) continuous integration testing. Every pull request and push must pass all checks before it can be merged into the `master` branch.

#### Continues Delivery
Killed by Google uses [Netlify](https://netlify.com) for hosting and continuous delivery. Netlify provides a publicly available deploy preview of your Pull Request and will build a new preview upon each push/update to your PR. The deploy preview will be evaluated manually by a maintainer before your PR is merged.

### Dependency Upgrades
Killed by Google is using [Dependabot](https://dependabot.com/) to keep dependencies updated. Generally, a maintainer will wrap any upgrades issued by Dependabot in the `upgrades` branch, merge, and automatically close any Dependabot PRs. Any dependency upgrades must pass CI and CD checks.
