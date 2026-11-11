<div align="center">

<img src="docs/assets/logo.svg" alt="Open Files v3 logo" width="150">

<h1>Open Files v3</h1>

<p><strong>Find and kill processes with open files that keep the array from stopping cleanly on <a href="https://unraid.net/">Unraid</a>.</strong></p>

<p>
  <a href="https://github.com/andrebrait/unraid-openfiles/releases"><img src="https://img.shields.io/github/v/release/andrebrait/unraid-openfiles?label=release&color=blue" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/Unraid-7.0%2B-e8543f" alt="Supported Unraid versions">
  <a href="https://github.com/andrebrait/unraid-openfiles/releases"><img src="https://img.shields.io/github/downloads/andrebrait/unraid-openfiles/total?color=blueviolet" alt="Downloads"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/andrebrait/unraid-openfiles?color=green" alt="License: GPL-3.0"></a>
</p>

</div>

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