# Markata plugin template

This is a [copier](https://copier.readthedocs.io/en/stable/) template for
creating [markata](https://markata.dev) plugins that is built into the markata
base cli.

## Usage

Using with the the markata base_cli.

``` bash
markata new plugin
# if paired with `markata new blog` it will be pre-filled wtih everything except the plugin name
```

Using straight with copier.

``` bash
copier copy git+https://github.com/WaylonWalker/markata-plugin-template .
```

## What you get

A plugin at
`<python_package_import_name>/plguins/<python_plugin_import_name>.py` that
contains a hook into every `markata` lifecycle method.  You can strip out the
ones that you don't need.
