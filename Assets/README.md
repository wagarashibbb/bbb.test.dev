![](https://github.com/bbb-behabeer/bbb.test.dev/workflows/Publish%20UPM%20Package/badge.svg)

# bbb test

## Installation

```bash
upm add package dev.wagarashibbb.upm.bbb.test.dev
```

Note: `upm` command is provided by [this repository](https://github.com/upm-packages/upm-cli).

You can also edit `Packages/manifest.json` directly.

```jsonc
{
  "dependencies": {
    // (snip)
    "dev.wagarashibbb.upm.bbb.test.dev": "[latest version]", 
    // (snip)
  },
  "scopedRegistries": [
    {
      "name": "Unofficial Unity Package Manager Registry",
      "url": "https://upm-packages.dev",
      "scopes": [
        "dev.wagarashibbb.upm"
      ]
    }
  ]
}
```

## Usages

* 
