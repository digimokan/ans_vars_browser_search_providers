# ans_role_vars_browser_search_providers

Define browser search provider names, urls, and hotkeys.

[![Release](https://img.shields.io/github/release/digimokan/ans_role_vars_browser_search_providers.svg?label=release)](https://github.com/digimokan/ans_role_vars_browser_search_providers/releases/latest "Latest Release Notes")
[![License](https://img.shields.io/badge/license-MIT-blue.svg?label=license)](LICENSE.md "Project License")

## Table Of Contents

* [Purpose](#purpose)
* [Quick Start](#quick-start)
    * [Use From Playbook](#use-from-playbook)
* [Role Vars](#role-vars)
* [Contributing](#contributing)

## Purpose

* Define browser search provider names (e.g. google, stackoverflow).
* Define hotkeys and url-search-strings for each search provider.
* Define a "default" browser search provider.

## Quick Start

### Use From Playbook

1. Create `requirements.yml` in ansible project root, and add this content:

   ```yaml
   # requirements.yml
   - src: https://github.com/digimokan/ans_role_vars_browser_search_providers
   ```

2. From the project root directory, install/download the role:

   ```shell
   $ ansible-galaxy install --role-file requirements.yml --roles-path ./roles --force-with-deps
   ```

   * _NOTE:_ `--force-with-deps` _ensures subsequent calls download updates_

3. Include the role with `import_role`, from the project playbook:

   ```yaml
   # playbook.yml
   - hosts: localhost
     connection: local
     tasks:
       - name: "Define browser search provider names, urls, and hotkeys"
         ansible.builtin.import_role:
           name: ans_role_vars_browser_search_providers
           public: true
   ```

## Role Vars

See the role `vars` file:

  * [vars/main.yml](../vars/main.yml)

## Contributing

* Feel free to report a bug or propose a feature by opening a new
  [Issue](https://github.com/digimokan/ans_role_vars_browser_search_providers/issues).
* Follow the project's [Contributing](CONTRIBUTING.md) guidelines.
* Respect the project's [Code Of Conduct](CODE_OF_CONDUCT.md).

