# Roc website

[![Build](https://github.com/jevinskie/roc-streaming-site/workflows/build/badge.svg)](https://github.com/jevinskie/roc-streaming-site/actions)

This repo contains the source code and the build script for [Roc - FLAC WIP website](https://jevinskie.github.io/roc-streaming-site/).

It has two branches:

* `jevinskie/content/feat/flac` — holds static content (in `www`) and GitHub Actions job to build and publish static content;
* `jevinskie/content/feat/flac` — holds automatically published content for GitHub pages.

The job fetches and builds Roc Toolkit documentation, merges it with pre-defined static content, and deploys the result to the `jevinskie/content/feat/flac` branch, which is then used by GitHib pages to render the website.
