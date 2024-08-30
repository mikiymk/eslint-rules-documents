# no-class-assign

`class`宣言で宣言した識別子に再代入をすることを禁止します。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint no-class-assign: ["error"] */

class A {
  a() {
    let A = 0;
  }
}

let B = class { }
B = 0;
```



## 間違いの例

```js
/* eslint no-class-assign: ["error"] */

class A {
  a() {
    A = 0;
  }
}

let B = class B { }
B = 0;
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/no-class-assign)
