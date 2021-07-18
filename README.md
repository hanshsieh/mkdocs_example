# Introduction
This repo shows an example for MkDocs.  
Checkout the [official document](https://www.mkdocs.org/) for the details of MkDocs.  
[Here's](https://squidfunk.github.io/mkdocs-material/getting-started/) another good document written by the author of `material` theme.  
This example uses the `material` theme. Check out [here](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes) for the other themes.
MkDocs uses `Python-Markdown` to generate web page from Markdown.
See [here](https://facelessuser.github.io/pymdown-extensions/) for the extensions you can use.
See [here](https://hanshsieh.github.io/mkdocs_example) for the resulting pages.

# Prerequisite
First, you need to have Python3.
Then, we need to install some tools if you don't already have.
```
pip3 install mkdocs
pip3 install pymdown-extensions
pip3 install mkdocs-mermaid2-plugin
# For the "material" theme
pip3 install mkdocs-material
```
To upgrade a tool, use something like
```bash
pip3 install mkdocs --upgrade
```

# Serve
Use the following command to serve the document locally.
```bash
python3 -m mkdocs serve
```

# Build
Use the following command to build the static files.
```bash
python3 -m mkdocs build
```

# Publish
See [here](https://www.mkdocs.org/user-guide/deploying-your-docs/) for the details.