# @joggerdocs/fastify-contract-generator

![CI](https://github.com/@joggerdocs/fastify-contract-generator/workflows/CI/badge.svg)
[![NPM version](https://img.shields.io/npm/v/@joggerdocs/fastify-contract-generator.svg?style=flat)](https://www.npmjs.com/package/@joggerdocs/fastify-contract-generator)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://standardjs.com/)

Automatically generate types and fixtures for based on route JSON Schema definitions, for frontends, dependent services, or SDKs.

## How to use

TBD

<details>
  <summary>
    Example Output
  </summary>
</details>

## Example

```javascript
const fastify = require('fastify')
const autoload = require('@joggerdocs/fastify-contract-generator')

const app = fastify()

app.register(contractGenerator)

app.listen({ port: 3000 })
```

```typescript
import fastify from 'fastify'
import autoload from '@joggerdocs/fastify-contract-generator'

const app = fastify()

app.register(contractGenerator)

app.listen({ port: 3000 })
```

## Configuration

TBD
