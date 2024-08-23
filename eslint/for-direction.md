# for-direction

`for`ループのカウンターが正しい方向に動くことを要求します。

次のリストは無限ループになる可能性があり、不正なカウンターの移動です。

- 条件部がカウンター変数より小さい`i >`、またはカウンター変数以下`i >=`であり、イテレーション部がカウンター変数を減らす操作。
- 条件部がカウンター変数より大きい`i <`、またはカウンター変数以上`i <=`であり、イテレーション部がカウンター変数を増やす操作。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint for-direction: "error" */

for (let i = 0; i < 10; i++) {
  doSomething(i);
}

for (let i = 10; i >= 0; i--) {
  doSomething(i);
}
```

## 間違いの例

```js
/* eslint for-direction: "error" */

for (let i = 0; i > 10; i++) {
  doSomething(i);
}

for (let i = 0; i <= 10; i--) {
  doSomething(i);
}
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/for-direction)
