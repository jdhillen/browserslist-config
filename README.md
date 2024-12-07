# @jdhillen/browserslist-config

ESM Browserslist configuration with multiple presets.

## Requirements

- Node.js >= 20.0.0
- Browserslist ^4.22.2

## Install

```bash
npm install -D @jdhillen/browserslist-config browserslist
```

## Usage

Add to package.json:

### Default Config

```json
{
  "browserslist": [
    "extends @jdhillen/browserslist-config"
  ]
}
```

### Modern Config

```json
{
  "browserslist": [
    "extends @jdhillen/browserslist-config/modern"
  ]
}
```

### Legacy Config

```json
{
  "browserslist": [
    "extends @jdhillen/browserslist-config/legacy"
  ]
}
```

## Available Configurations

- defaults: Latest 2 versions of major browsers
- modern: Latest version of major browsers
- legacy: Latest 4 versions plus ESR and Node.js LTS
