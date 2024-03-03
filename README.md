<p align="center">
  <a href="https://geison.dev/">
    <img width="100" src="https://geison.dev/assets/icons/logo.svg" alt="Logo" />
  </a>
</p>

<h1 align="center">
	Type Checker
</h1>
<div align="center">

Easy to use, fast and lightweight library for Node.js.

<a>
	<img src="https://img.shields.io/github/license/geisonjr/type-checker?style=flat" alt="MIT Licence" />
</a>
<a href="https://www.npmjs.com/package/@geisonjr/type-checker">
	<img src="https://img.shields.io/npm/v/@geisonjr/type-checker?style=flat-square" alt="NPM version" />
</a>
<a href="https://www.npmjs.com/package/@geisonjr/type-checker">
	<img src="https://img.shields.io/npm/dt/@geisonjr/type-checker?style=flat-square" alt="NPM downloads" />
</a>
</div>

> [!WARNING]
> This project is under development and is not yet ready for use.

## 🌱 Overview

This library is a collection of functions that help you to check the type of a variable in JavaScript and TypeScript.

## ✨ Features

- [x] isArray
- [x] isArrayBuffer
- [x] isBigInt
- [x] isBlob
- [x] isBoolean
- [x] isBuffer
- [x] isDate
- [x] isEnum
- [x] isError
- [x] isFalsy
- [x] isFunction
- [x] isNaNumber
- [x] isNothing
- [x] isNull
- [x] isNullOrUndefined
- [x] isNumber
- [x] isObject
- [x] isPromise
- [x] isRegExp
- [x] isString
- [x] isSymbol
- [x] isTruthy
- [x] isUndefined
- [x] isURL
- [x] isURLSearchParams
- [x] isVoid

## 🚀 Tecnologies

The following tools were used in the construction of the project:

- [Jest](https://jestjs.io/)
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)

## 📦 Install

Use the package manager [npm](https://docs.npmjs.com/),
[yarn](https://yarnpkg.com).

```bash
npm install @geisonjr/type-checker
```

```bash
yarn add @geisonjr/type-checker
```

## 🏗️ Usage

### Example with True Condition

```typescript
import '@geisonjr/type-checker'

let test: any = true // false

// Is `true` if the value is a boolean type
if (isBoolean(test)) {
	// The intelisense will be recognize the variable as a boolean
	console.log('This is a boolean')
}

// Output: This is a boolean
```

### Example with False Condition

```typescript
import '@geisonjr/type-checker'

let test: any = '123'

// Is `true` if the value is a number type
if (isNumber(test)) {
	// The intelisense will be recognize the variable as a number
	console.log('This is a number')
} else {
	// The intelisense will be recognize the variable not as a number
	console.log('This is not a number')
}

// Output: This is not a number
```

## 📋 License

This project is under the
[MIT License](https://github.com/geisonjr/type-checker/blob/master/LICENSE)
