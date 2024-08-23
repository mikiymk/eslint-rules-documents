# no-async-promise-executor

`new Promise`コンストラクターの引数に渡す`executor`コールバック関数を`async`キーワードを使った非同期関数にすることを禁止します。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint no-async-promise-executor: "error" */

let p = new Promise(function (resolve, reject) {
  asyncFunction(
    function (data) {
      resolve(data);
    },
    function (error) {
      reject(error);
    },
  );
});
```

## 間違いの例

```js
/* eslint no-async-promise-executor: "error" */

let p = new Promise(async function (resolve, reject) {
  await asyncFunction(
    function (data) {
      resolve(data);
    },
    function (error) {
      reject(error);
    },
  );
});
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/no-async-promise-executor)
