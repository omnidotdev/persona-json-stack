<div align="center">

# persona.json

Portable non-human identity specification

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE.md)

</div>

## Overview

persona.json is a composable JSON schema for defining non-human identities -- AI assistants, brands, bots, mascots, characters, and any other entity that presents a public-facing identity. Designed for portability across platforms and products.

## Services

| Service | Description |
|---------|-------------|
| [persona-json-schema](https://github.com/omnidotdev/persona-json-schema) | JSON Schema specification |
| [persona-json-site](https://github.com/omnidotdev/persona-json-site) | Landing page at [persona.omni.dev](https://persona.omni.dev) |

## Quick Start

```bash
# Clone with services
git clone https://github.com/omnidotdev/persona-json
cd persona-json
git clone https://github.com/omnidotdev/persona-json-schema services/persona-json-schema
git clone https://github.com/omnidotdev/persona-json-site services/persona-json-site
```

## Relationship to life.json

| Spec | Describes | Owned by |
|------|-----------|----------|
| [life.json](https://life.omni.dev) | Human identity | The user |
| persona.json | Non-human identity | The operator/developer |

They meet in the middle: life.json's `assistants` slice stores the relationship between a specific human and a specific persona (learned facts, permissions, preferences).

## License

The code in this repository is licensed under Apache 2.0, &copy; [Omni LLC](https://omni.dev). See [LICENSE.md](LICENSE.md) for more information.
