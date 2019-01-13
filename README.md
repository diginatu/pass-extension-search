pass inc
========

A [pass](https://www.passwordstore.org/) extension that enables to search password interactively.

![animation gif](./record.gif)

## Installation

1. Enable password-store extensions by setting `PASSWORD_STORE_ENABLE_EXTENSIONS=true`
2. Copy `./inc.bash` to your extension folder (Or run Install.bash)

## Usage

* `pass inc` to start and type keywords to search passwords.
* Keywords can be some parts of password path split by spaces.
* `<Ctrl-N>`/`<Ctrl-P>` or `<Down>`/`<Up>` to navigate the cursor.
* Options --clip, -c are passed into the pass command.
