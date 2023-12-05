Repository for the documentation of the Digital Hub.

New pages can be created by writing *.md* files. To enable and add a page to the navigation, add the path to your file to the `nav` element in *mkdocs.yml*.

## Run locally
``` shell
cd user
mkdocs serve
```
The documentation site will be available at *localhost:8000*.

## Deploy
``` shell
cd user
mkdocs gh-deploy -b gh-pages-user
```
MkDocs will generate the site and automatically push it to the pages branch. It will be available [here](https://scc-digitalhub.github.io/docs/) (changes may take a couple minutes to become effective).
