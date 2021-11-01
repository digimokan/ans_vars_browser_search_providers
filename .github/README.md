# ans_role_vars_browser_search_providers

Define browser search provider names, urls, and hotkeys.

[![Release](https://img.shields.io/github/release/digimokan/ans_role_vars_browser_search_providers.svg?label=release)](https://github.com/digimokan/ans_role_vars_browser_search_providers/releases/latest "Latest Release Notes")
[![License](https://img.shields.io/badge/license-MIT-blue.svg?label=license)](LICENSE.md "Project License")

## Table Of Contents

* [Purpose](#purpose)
* [Requirements](#requirements)
* [Supported Operating Systems](#supported-operating-systems)
* [Quick Start](#quick-start)
    * [Use From Another Role](#use-from-another-role)
* [Role Options](#role-options)
* [Contributing](#contributing)

## Purpose

* Define browser search provider names (e.g. google, stackoverflow)
* Define hotkeys and url-search-strings for each search provider
* Define a "default" browser search provider

## Supported Operating Systems

* Arch Linux
* FreeBSD

## Quick Start

### Use From Another Role

1. Create `meta/requirements.yml` in role root dir, and add this content:

   ```yaml
   # requirements.yml
   - src: https://github.com/digimokan/ans_role_vars_browser_search_providers
   ```

## Role Options

See the role `defaults` file, for overridable vars:

  * [defaults/main.yml](../defaults/main.yml)

## Contributing

* Feel free to report a bug or propose a feature by opening a new
  [Issue](https://github.com/digimokan/ans_role_vars_browser_search_providers/issues).
* Follow the project's [Contributing](CONTRIBUTING.md) guidelines.
* Respect the project's [Code Of Conduct](CODE_OF_CONDUCT.md).

