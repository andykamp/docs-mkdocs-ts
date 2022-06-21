# Mkdocs documentation template

Documentation was added top this project using [mkdocs](https://https://squidfunk.github.io/mkdocs-material/)
The only command needed was `mkdocs new .`

Then both a mkdocs.yml and a docs/index.md is created for you:
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

The following commands can be used to serve and buld the docs
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* `mkdocs gh-deploy --force` - Manually build and deploy the docs using github pages


To deploy the documentation we use github pages. 
We added a **./github/workflows/ci.yml** that builds and depoyes the docs on every push to the master/main branch
You can also deploy it manually by doin a `mkdocs gh-deploy --force`


