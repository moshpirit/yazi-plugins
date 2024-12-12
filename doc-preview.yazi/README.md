# doc-preview.yazi

Uses [antiword](https://github.com/grobian/antiword) to enable MS Word (version 2, 6, 7, 97, 2000 and 2003) DOC files preview in [yazi](https://github.com/sxyazi/yazi).

# docx-preview.yazi

Use [docx2txt](https://docx2txt.sourceforge.net/) to preview DOCX files in [yazi](https://github.com/sxyazi/yazi).

## Requirements

- [antiword](https://github.com/grobian/antiword) - It's probably available in your package manager.

## Installation

Install with:

```sh
ya pack -a lpanebr/yazi-plugins:doc-preview.yazi
```

and enable by adding it to your `yazi.toml` config file:

```toml
[plugin]
prepend_previewers = [
    { name = "*.doc", run = "doc-preview"},
]
```
