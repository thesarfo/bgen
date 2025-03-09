Converts blog posts written in custom markup/markdown to HTML files with proper formatting.

### Features

- Parses custom blog post format
- Renders posts into HTML
- Command-line interface
- Customizable HTML templates

### Build with Stack
```bash
stack setup
stack build
stack exec bgen
```

### Or Build with Cabal
```bash
cabal update
cabal build
cabal run bgen
```

### Usage

```bash
stack exec bgen -- <your-input-file.md> <output-directory>
```