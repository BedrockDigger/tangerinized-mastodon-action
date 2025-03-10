# tangerinized-mastodon-action
[![Build Mastodon Docker Images](https://github.com/BedrockDigger/tangerinized-mastodon-action/actions/workflows/build-image.yml/badge.svg)](https://github.com/BedrockDigger/tangerinized-mastodon-action/actions/workflows/build-image.yml)

A GitHub Action for building [Mastodon](https://github.com/mastodon/mastodon) with [Tangerine UI](https://github.com/nileane/TangerineUI-for-Mastodon).
- Automatically checks for new Mastodon releases daily.
- Pushes to any specified Docker Hub repository.

Add `DOCKERHUB_NAMESPACE`, `DOCKERHUB_REPOSITORY`, `DOCKERHUB_TOKEN` and `DOCKERHUB_USERNAME` in Settings > Security > Secrets and variables > Actions > Secrets first before running.