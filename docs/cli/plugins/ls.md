## `mise plugins ls [OPTIONS]`

**Aliases:** `list`

```text
List installed plugins

Can also show remotely available plugins to install.

Usage: plugins ls [OPTIONS]

Options:
  -c, --core
          The built-in plugins only
          Normally these are not shown

      --user
          List installed plugins
          
          This is the default behavior but can be used with --core
          to show core and user plugins

  -u, --urls
          Show the git url for each plugin
          e.g.: https://github.com/asdf-vm/asdf-nodejs.git

Examples:

    $ mise plugins ls
    node
    ruby

    $ mise plugins ls --urls
    node    https://github.com/asdf-vm/asdf-nodejs.git
    ruby    https://github.com/asdf-vm/asdf-ruby.git
```