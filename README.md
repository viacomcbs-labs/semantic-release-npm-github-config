# semantic-release-npm-github-config

<p>
  <a href="https://github.com/viacomcbs-labs/semantic-release-npm-github-config/actions/workflows/publish.yml" target="_blank">
    <img alt="Publish" src="https://github.com/viacomcbs-labs/semantic-release-npm-github-config/actions/workflows/publish.yml/badge.svg?branch=master">
  </a>
  <a href="https://www.npmjs.com/package/@viacomcbs-labs/semantic-release-npm-github-config" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/@viacomcbs-labs/semantic-release-npm-github-config.svg">
  </a>
  <a href="https://github.com/viacomcbs-labs/semantic-release-npm-github-publish#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/viacomcbs-labs/semantic-release-npm-github-publish/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/viacomcbs-labs/semantic-release-npm-github-publish/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> [**Semantic-release**](https://github.com/semantic-release/semantic-release) shareable configuration for easy publishing to NPM [Github Package Registry](https://github.com/features/packages).

## About

> This [sharable configuration](https://github.com/semantic-release/semantic-release/blob/master/docs/extending/shareable-configurations-list.md) conforms to [Conventional Commits spec](https://www.conventionalcommits.org/)

### Using plugins

 - [@semantic-release/commit-analyzer](https://github.com/semantic-release/commit-analyzer)
   Ensures that commits are conformed to the [conventional commits specification](https://www.conventionalcommits.org/en/v1.0.0/)
 - [@semantic-release/release-notes-generator](https://github.com/semantic-release/release-notes-generator)
   Generate changelog content with [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog)
- [@semantic-release/github](https://github.com/semantic-release/release-notes-generator)
   Publish a [GitHub release](https://help.github.com/articles/about-releases) and comment on released Pull Requests.

