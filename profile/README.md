# <img src="https://raw.githubusercontent.com/fileporter/fileporter/master/README.assets/repo-icon.png" alt="" style="display: inline-block; height: 30px;" /> fileporter
Serve a directory in your local network for view over the browser

fileporter is a small read-only file-server to give you good access to some files without the need to download them onto the other device or install some software there.

See [the documentation](https://fileporter.github.io/docs/) for more or to get started.

## File-Supports

- text
  - all text files are readable
  - code-files get automatic syntax-highlighting
  - special support for file-formats like markdown or json
- videos
  - all common video formats should be supported
- images
  - all common video formats should be supported
- audio
  - all common audio formats should be supported
- special-files
  - pdf
  - ~~doc/docx~~
  - ~~archives (zip/tar)~~

## Platform support

<!-- ✓ ✅ ❌ ❓ ⓘ -->

| Platform | Supported     | Installer     | Tested |
|----------|---------------|---------------|--------|
| Linux    | ✅             | ✅             | ✅      |
| Windows  | ✅<sup>ⓘ</sup> | ❌             | ❌      |
| MacOS    | ✅<sup>ⓘ</sup> | ✅<sup>ⓘ</sup> | ❌      |

<small>ⓘ should work. But some adjustments could be needed</small>

## Stats and technical information

[![pages-build-deployment](https://github.com/fileporter/docs/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/fileporter/docs/actions/workflows/pages/pages-build-deployment)
[![CodeQL](https://github.com/fileporter/fileporter/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/fileporter/fileporter/actions/workflows/github-code-scanning/codeql)

![last commit](https://img.shields.io/github/last-commit/fileporter/fileporter)

![repo size](https://img.shields.io/github/repo-size/fileporter/fileporter?logo=github)
![code size](https://img.shields.io/github/languages/code-size/fileporter/fileporter?logo=github)
![total lines](https://img.shields.io/tokei/lines/github/fileporter/fileporter?logo=github)

<sup>requires</sup>
![python-version](https://img.shields.io/github/pipenv/locked/python-version/fileporter/fileporter)
