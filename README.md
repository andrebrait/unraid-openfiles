Open Files v3 for Unraid Server
===============================

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![GitHub Releases](https://img.shields.io/github/v/release/andrebrait/unraid-openfiles)](https://github.com/andrebrait/unraid-openfiles/releases)
[![Last Commit](https://img.shields.io/github/last-commit/andrebrait/unraid-openfiles)](https://github.com/andrebrait/unraid-openfiles/commits/main/)
[![Code Style: PHP-CS-Fixer](https://img.shields.io/badge/code%20style-php--cs--fixer-brightgreen.svg)](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/andrebrait/unraid-openfiles/total)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/andrebrait/unraid-openfiles/latest/total)

## Fork notice

This is a maintained fork of [dkaser/unraid-openfiles](https://github.com/dkaser/unraid-openfiles) by Derek Kaser, based on the original work by Dan Landon. This fork carries on maintaining the plugin and publishes its own releases.

### Installation

In the Unraid web UI, go to **Plugins → Install Plugin** and enter:

```
https://raw.githubusercontent.com/andrebrait/unraid-openfiles/main/plugin/open.files3.plg
```

Installing replaces the previous Open Files plugin (the original `open.files`, or an earlier release of this fork) and keeps your settings. The plugin was renamed to `open.files3` ("Open Files v3") so Community Applications can tell it apart from the original.

### Requirements

- Unraid 7.0.0 or later.

### Issues

Report bugs and feature requests in the [issue tracker of this fork](https://github.com/andrebrait/unraid-openfiles/issues).

This plugin adds the ability to monitor processes that have open files that might keep the aray from shutting down cleanly.  You can kill any processes that have open files preventing array shutdown.  This plugin requires Unraid 7.0.0 or later.

## CI maintenance

Workflow actions use SHA-pinned versions of their latest available major releases. The custom release-drafter pin is retained because its conventional-commit changes are not on the upstream default branch. The PHP-CS-Fixer Docker action continues to track its `latest` image.