# @hookstate/validation

[![license](https://img.shields.io/github/license/avkonst/hookstate)](https://img.shields.io/github/license/avkonst/hookstate) [![npm version](https://img.shields.io/npm/v/@hookstate/validation.svg?maxAge=300&label=version&colorB=007ec6)](https://www.npmjs.com/package/@hookstate/validation)

Plugin for @hookstate/core to enable validation of data state. See [demo](https://hookstate.netlify.com/plugin-validation).

This plugin requires the target environment to support `Array.from`, `Array.includes` and `Object.values`, which can be polyfilled using `core-js`.