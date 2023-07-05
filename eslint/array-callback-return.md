# array-callback-return

以下の関数の引数に渡すコールバック関数は値を返さないものをチェックします。

- Array.from
- Array.prototype.every
- Array.prototype.filter
- Array.prototype.find
- Array.prototype.findIndex
- Array.prototype.findLast
- Array.prototype.findLastIndex
- Array.prototype.flatMap
- Array.prototype.map
- Array.prototype.reduce
- Array.prototype.reduceRight
- Array.prototype.some
- Array.prototype.sort
- Array.prototype.toSorted

オプションによって以下の関数もチェックします。

- Array.prototype.forEach

値を返す関数は
すべてのパスで値のある `return` 文がある関数
波括弧の省略記法を使ったアロー関数

値を返さない関数は
少なくとも一つのパスで値のない `return` 文がある関数
少なくとも一つのパスで `return` 文がない関数

## Options

オプションは1つのオブジェクトを受け入れます。

```ts
type Options = {
  allowImplicit: boolean;
  checkForEach: boolean;
};

const OptionDefault = {
  allowImplicit: false,
  checkForEach: false,
};
```

### allowImplicit

`true` に設定されているとき、値のない `return` 文による暗黙的な `undefined` を返すことを許可します。

<details>
<summary>有効な例</summary>
  
```js
/* eslint array-callback-return: ["error", { allowImplicit: true }] */

new Array(5).map(function() {
  return;
});
```
</details>

<details>
<summary>無効な例</summary>
  
```js
/* eslint array-callback-return: ["error", { allowImplicit: true }] */

new Array(5).map(function() {
  // no return starement
});
```
</details>

### checkForEach

`true` に設定されているとき、 `Array.prototype.forEach` のコールバック関数で値を返すものをチェックします。
