# Hello

A sample plugin for [Textus](https://textus.md): it counts the words of the document in front, and lists its headings in the sidebar.

This repository is laid out as **Export for Publishing** in Textus lays out a plugin, and is listed the way any plugin from outside CatVinci Studio is (see [LISTING.md](https://github.com/CatVinci-Studio/textus-plugins/blob/main/LISTING.md)). Start yours from it.

## Install

Download `sample.hello-<version>.zip` from this repository's [releases](../../releases), then in Textus choose **Settings › Extensions › Plugins › Install from file…** and pick it.

## Use

See [USAGE.md](USAGE.md).

## Publish a new version

1. Change `version` in `textus-plugin.json` (for example to `0.2.0`).
2. Commit, then tag the commit with the same version and push the tag: `git tag v0.2.0 && git push origin v0.2.0`. The release workflow publishes `sample.hello-0.2.0.zip`.
