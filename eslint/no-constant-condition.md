# no-constant-condition

常に一定の条件部をチェックします。

`if` `for` `while` `do-while`または条件演算子の条件部が
常に truthy または falthy な値のとき、間違っている可能性があります。

## Options

1つのオブジェクトオプションを受け入れます。

```ts
type Options = {
  checkLoops: boolean;
};

const Defaults = {
  checkLoops: true,
};
```

### checkLoops

`true` のとき、 `for` `while` `do-while` の条件部をチェックします。

## Configs

以下の設定で使用されています

- `"eslint:recommended": "error"`

## rules

- https://eslint.org/docs/latest/rules/no-constant-condition
