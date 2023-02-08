# ESNext Promise

<p align='center'>Next Generation ECMAScript Promise Objects</p>

<br>

<p align='center'>
  English | <a href='./README.zh-CN.md'>简体中文</a>
</p>

ESNext Promise, AKA "Post-ES6-era Promise", is based on ECMAScript Language Specification(AKA ECMA-262 Standards) & Promises/A+ Specification.

## TDD(Test-Driven Development)

- [x] Promises/A+ Compliance Test Suite

## Promise Objects

- [x] The Promise Constructor
  - [x] Promise(executor)
- [ ] Properties of the Promise Prototype Object
  - [x] Promise.prototype.then(onFulfilled, onRejected)
- [x] Properties of Promise Instances

## How to run unit tests

```bash
# step1: clone the repo
git clone https://github.com/jklover1110/esn-promise.git

# step 2: install 3rd-party node modules
npm i -g pnpm
pnpm install

# step 3: run unit tests
pnpm test

# step 4: use Promises/A+ compliance test suite
pnpm aplus

```
