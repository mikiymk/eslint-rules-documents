# constructor-super

クラスのコンストラクター内部で正しい`super`の呼び出しを要求します。

次のリストは不正な呼び出しです。

- 派生クラスではないクラスのコンストラクター内部で`super`を呼び出す。
- 派生クラスのコンストラクター内部で`super`を呼び出さない。
- 一つのコンストラクターで2回以上`super`を呼び出す。

## オプション

```ts
type Options = [];

const OptionDefault: Options = [];
```

## 正しい例

```js
/* eslint constructor-super: "error" */

class A {
  constructor() {}
}

class B extends A {
  constructor() {
    super();
  }
}
```

## 間違いの例

```js
/* eslint constructor-super: "error" */

class A {
  constructor() {
    super();
  }
}

class B extends A {
  constructor() {}
}

class C extends A {
  constructor() {
    super();
    super();
  }
}
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/constructor-super)
