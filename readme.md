# registry-info 

Get registry info (url, auth token, headers) from an arg

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install registry-info --save
```

## Usage

```js
import registryInfo from 'registry-info';

// returns an object with {registryUrl, authToken, authorization}
//  .authorization can be used in http headers
console.log(registryInfo());

// optionally a scope can be set
console.log(registryInfo(scope));

```

## Tests

```sh
npm install
npm test
```

## Dependencies

- [registry-auth-token](https://github.com/rexxars/registry-auth-token): Get the auth token set for an npm registry (if any)
- [registry-url](https://github.com/sindresorhus/registry-url): Get the set npm registry URL

## Dev Dependencies

- [babel-cli](https://github.com/babel/babel/tree/master/packages): Babel command line.
- [babel-core](https://github.com/babel/babel/tree/master/packages): Babel compiler core.
- [babel-preset-es2015](https://github.com/babel/babel/tree/master/packages): Babel preset for all es2015 plugins.
- [package-json-to-readme](https://github.com/zeke/package-json-to-readme): Generate a README.md from package.json contents
- [xo](https://github.com/sindresorhus/xo): JavaScript happiness style linter ❤️


## License

MIT

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_