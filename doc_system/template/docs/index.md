# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

TODO: Organize better, keep all **MRS** files (UML sources) in **spec** directory, while all non-spec files like .md and .drawio elsewhere

## Images from Draw.io source

> This works, but only through **mkdocs build**, and likely since a Display system is needed for serving

![](../images/example.drawio)

## Tables

{{ read_csv('../spec/test.csv') }}

## PlantUML Diagrams

TODO: Dark mode

![](uml/out/example.svg)