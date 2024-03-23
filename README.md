# inverse-lerp

[![npm version](https://img.shields.io/npm/v/inverse-lerp)](https://www.npmjs.com/package/inverse-lerp)
[![stability-stable](https://img.shields.io/badge/stability-stable-green.svg)](https://www.npmjs.com/package/inverse-lerp)
[![npm minzipped size](https://img.shields.io/bundlephobia/minzip/inverse-lerp)](https://bundlephobia.com/package/inverse-lerp)
[![dependencies](https://img.shields.io/librariesio/release/npm/inverse-lerp)](https://github.com/dmnsgn/inverse-lerp/blob/main/package.json)
[![types](https://img.shields.io/npm/types/inverse-lerp)](https://github.com/microsoft/TypeScript)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-fa6673.svg)](https://conventionalcommits.org)
[![styled with prettier](https://img.shields.io/badge/styled_with-Prettier-f8bc45.svg?logo=prettier)](https://github.com/prettier/prettier)
[![linted with eslint](https://img.shields.io/badge/linted_with-ES_Lint-4B32C3.svg?logo=eslint)](https://github.com/eslint/eslint)
[![license](https://img.shields.io/github/license/dmnsgn/inverse-lerp)](https://github.com/dmnsgn/inverse-lerp/blob/main/LICENSE.md)

Get a value's interpolant within a linear range, effectively remapping a value v within [a, b] to [0, 1].

[![paypal](https://img.shields.io/badge/donate-paypal-informational?logo=paypal)](https://paypal.me/dmnsgn)
[![coinbase](https://img.shields.io/badge/donate-coinbase-informational?logo=coinbase)](https://commerce.coinbase.com/checkout/56cbdf28-e323-48d8-9c98-7019e72c97f3)
[![twitter](https://img.shields.io/twitter/follow/dmnsgn?style=social)](https://twitter.com/dmnsgn)

![](https://raw.githubusercontent.com/dmnsgn/inverse-lerp/main/screenshot.gif)

## Installation

```bash
npm install inverse-lerp
```

## Usage

```js
import inverseLerp from "inverse-lerp";

const range = [20, 40];
const [a, b] = range;
const value = 30;
const t = inverseLerp(a, b, value);
// => 0.5
```

## API

<!-- api-start -->

Auto-generated API content.

<!-- api-end -->

## License

MIT. See [license file](https://github.com/dmnsgn/inverse-lerp/blob/main/LICENSE.md).
