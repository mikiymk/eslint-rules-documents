# for-direction

条件部とループ部の組み合わせから無限ループになる可能性がある `for` ループをチェックします。

- 条件部が 変数より小さい (`i >`) 変数以下 (`i >=`) の場合、カウントダウン操作 (`i--` や `i -= 1`)で無限ループになる可能性があります。
- 条件部が 変数より大きい (`i <`) 変数以上 (`i <=`) の場合、カウントアップ操作 (`i++` や `i += 1`)で無限ループになる可能性があります。

## Options

オプションを受け入れません。

## Configs

以下の設定で使用されています

- `"eslint:recommended": "error"`

## rules

- https://eslint.org/docs/latest/rules/for-direction
