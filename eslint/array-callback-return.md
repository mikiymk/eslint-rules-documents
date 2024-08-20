# array-callback-return

`Array`オブジェクトの関数の引数に渡すコールバック関数に必ず値を返すことを要求します。

コールバック関数を受け取る関数は次の関数です。

- `Array.from`
- `Array.prototype.every`
- `Array.prototype.filter`
- `Array.prototype.find`
- `Array.prototype.findIndex`
- `Array.prototype.findLast`
- `Array.prototype.findLastIndex`
- `Array.prototype.flatMap`
- `Array.prototype.map`
- `Array.prototype.reduce`
- `Array.prototype.reduceRight`
- `Array.prototype.some`
- `Array.prototype.sort`
- `Array.prototype.toSorted`

オプションによって以下の関数も検査します。

- `Array.prototype.forEach`

## オプション

```ts
type Options = [
  {
    allowImplicit?: boolean;
    checkForEach?: boolean;
    allowVoid?: boolean;
  },
];

const OptionDefault: Options = [
  {
    allowImplicit: false,
    checkForEach: false,
    allowVoid: false,
  },
];
```

### allowImplicit

`true`に設定されているとき、値のない`return`文による暗黙的な`undefined`を返すことを許可します。

### checkForEach

`true`に設定されているとき、`Array.prototype.forEach`の引数に渡すコールバック関数で値を返すことを禁止します。

### allowVoid

`true`に設定されているとき、`Array.prototype.forEach`の引数に渡すコールバック関数で`void`演算子の結果の値を返すことを許可します。

## 正しい例

```js
/* eslint array-callback-return: ["error"] */

array.map(function (item) {
  return item * 2;
});

array.filter((item) => item < 5);
```

```js
/* eslint array-callback-return: ["error", { allowImplicit: true }] */

array.map(function (item) {
  return;
});
```

```js
/* eslint array-callback-return: ["error", { checkForEach: true }] */

array.forEach(function (item) {
  doSomething(item);
});
```

```js
/* eslint array-callback-return: ["error", { checkForEach: true, allowVoid: true }] */

array.forEach(function (item) {
  return void doSomething(item);
});
```

## 間違いの例

```js
/* eslint array-callback-return: ["error"] */

array.map(function (item) {
  doSomething(item);
});
```

```js
/* eslint array-callback-return: ["error", { allowImplicit: true }] */

array.map(function () {
  doSomething(item);
});
```

```js
/* eslint array-callback-return: ["error", { checkForEach: true }] */

array.forEach(function (item) {
  return item * 2;
});
```

```js
/* eslint array-callback-return: ["error", { checkForEach: true, allowVoid: true }] */

array.forEach(function (item) {
  return doSomething(item);
});
```

## コンフィグ

以下の設定で使用されています。
