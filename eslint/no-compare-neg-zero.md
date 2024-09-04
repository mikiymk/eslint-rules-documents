# no-compare-neg-zero

`-0`と比較することを禁止します。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint no-compare-neg-zero: ["error"] */

x == 0;
x !== 0;
x < -1;
```



## 間違いの例

```js
/* eslint no-compare-neg-zero: ["error"] */

x == -0;
x !== -0;
x > -0;
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/no-compare-neg-zero)
