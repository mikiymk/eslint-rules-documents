# no-compare-neg-zero

負のゼロの比較演算をしないようにチェックします。

`+0` と `-0` は別の数値ですが、 `+0 === -0` は `true` になります。
代わりに `Object.is` を使用してください。

## Options

オプションを受け入れません。

## Configs

以下の設定で使用されています

- `"eslint:recommended": "error"`

## rules

- https://eslint.org/docs/latest/rules/no-compare-neg-zero
