# no-cond-assign

条件部での代入をチェックします。

`=` を使った代入式は値を返すことができますが、
`if` `for` `while` `do-while` の条件部で使用した場合は比較演算子
`==` `===` のミスタイプの可能性があります。

## Options

1つの文字列オプションを受け入れます。

```ts
type Options = "except-parens" | "always";

const Defaults = "expect-parens";
```

- `"except-parens"`
  括弧で囲まれていない代入式のみ報告されます。
- `"always"`
  すべての代入式が報告されます。

## Configs

以下の設定で使用されています

- `"eslint:recommended": "error"`

## rules

- https://eslint.org/docs/latest/rules/no-cond-assign
