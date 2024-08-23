# no-await-in-loop

ループの中で`await`演算子の使用を禁止します。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint no-await-in-loop: "error" */

for (let i = 0; i < array.length; i++) {
  const item = array[i];
}

for await (const item of promises) {
  doSomething(item);
}
```

## 間違いの例

```js
/* eslint no-await-in-loop: "error" */

for (let i = 0; i < array.length; i++) {
  const item = await array[i];
}
```

## コンフィグ

以下の設定で使用されています。

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/no-await-in-loop)
