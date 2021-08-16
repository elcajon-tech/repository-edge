# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/elcajon/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Duplicati][addon-duplicati]

![Latest Version][duplicati-version-shield]
![Supports armhf Architecture][duplicati-armhf-shield]
![Supports armv7 Architecture][duplicati-armv7-shield]
![Supports aarch64 Architecture][duplicati-aarch64-shield]
![Supports amd64 Architecture][duplicati-amd64-shield]
![Supports i386 Architecture][duplicati-i386-shield]

Duplicati Home Assistant Add-on

[:books: Duplicati add-on documentation][addon-doc-duplicati]

### &#10003; [Nextcloud][addon-nextcloud]

![Latest Version][nextcloud-version-shield]
![Supports armhf Architecture][nextcloud-armhf-shield]
![Supports armv7 Architecture][nextcloud-armv7-shield]
![Supports aarch64 Architecture][nextcloud-aarch64-shield]
![Supports amd64 Architecture][nextcloud-amd64-shield]
![Supports i386 Architecture][nextcloud-i386-shield]

Nextcloud Home Assistant Add-on

[:books: Nextcloud add-on documentation][addon-doc-nextcloud]

### &#10003; [Visual Studio Code][addon-vscode]

![Latest Version][vscode-version-shield]
![Supports armhf Architecture][vscode-armhf-shield]
![Supports armv7 Architecture][vscode-armv7-shield]
![Supports aarch64 Architecture][vscode-aarch64-shield]
![Supports amd64 Architecture][vscode-amd64-shield]
![Supports i386 Architecture][vscode-i386-shield]

Fully featured VSCode experience, to edit your HA config in the browser, including auto-completion!

[:books: Visual Studio Code add-on documentation][addon-doc-vscode]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

- [Open an issue for the add-on: Duplicati][duplicati-issue]
- [Open an issue for the add-on: Nextcloud][nextcloud-issue]
- [Open an issue for the add-on: Visual Studio Code][vscode-issue]

For a general repository issue or add-on ideas [open an issue here][issue]





## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-duplicati]: https://github.com/elcajon/addon-duplicati/tree/v1.0.3
[addon-doc-duplicati]: https://github.com/elcajon/addon-duplicati/blob/v1.0.3/README.md
[duplicati-issue]: https://github.com/elcajon/addon-duplicati/issues
[duplicati-version-shield]: https://img.shields.io/badge/version-v1.0.3-blue.svg
[duplicati-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[duplicati-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[duplicati-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[duplicati-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[duplicati-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-nextcloud]: https://github.com/elcajon/addon-nextcloud/tree/880723d
[addon-doc-nextcloud]: https://github.com/elcajon/addon-nextcloud/blob/880723d/README.md
[nextcloud-issue]: https://github.com/elcajon/addon-nextcloud/issues
[nextcloud-version-shield]: https://img.shields.io/badge/version-880723d-blue.svg
[nextcloud-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nextcloud-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nextcloud-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nextcloud-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[nextcloud-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-vscode]: https://github.com/elcajon/addon-vscode/tree/1047182
[addon-doc-vscode]: https://github.com/elcajon/addon-vscode/blob/1047182/README.md
[vscode-issue]: https://github.com/elcajon/addon-vscode/issues
[vscode-version-shield]: https://img.shields.io/badge/version-1047182-blue.svg
[vscode-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[vscode-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[vscode-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[vscode-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[vscode-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[gitlabci-shield]: https://gitlab.com/elcajon/repository-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/elcajon/repository-edge/pipelines
[issue]: https://github.com/elcajon/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/elcajon/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html