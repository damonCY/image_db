# image_db

A simple GitHub-hosted image repository used as the storage layer for image assets.

## Overview

This repository keeps uploaded image files under the `data/` directory and can be used as:

- a lightweight personal image gallery
- a backing repository for `git-pictures-bed`
- a simple way to store and reference static image assets through GitHub raw URLs

## Structure

```text
data/
```

The `data/` directory contains the uploaded image files.

## Typical Usage

This repository is designed to work well with tools that push images into a GitHub repository and then serve them through raw content links.

Example raw URL pattern:

```text
https://raw.githubusercontent.com/<owner>/<repo>/master/data/<file-name>
```

## Related Project

- [git-pictures-bed](https://github.com/damonCY/git-pictures-bed) — CLI and local web uploader for managing images in a GitHub repository
