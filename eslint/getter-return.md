# getter-return

ゲッターの内部で値を返す `return` 文があることをチェックします。

## Options

1つのオブジェクトオプションを受け入れます。

```ts
type Options = {
  allowImplicit: boolean;
};

const Defaults = {
  allowImplicit: false,
};
```

### allowImplicit

`true` の場合、値のない `return` 文が暗黙的な `undefined` を返すことを許可します。

## Configs

以下の設定で使用されています

- `"eslint:recommended": "error"`

## rules

- https://eslint.org/docs/latest/rules/getter-return
