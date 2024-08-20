# getter-return

ゲッター関数で必ず値を返すことを要求します。

## オプション

```ts
type Options = [] | [
 {
  allowImplicit?: boolean;
}
 ];

const OptionDefault: Options = [{
  allowImplicit: false,
}];
```

### allowImplicit

`true`に設定されているとき、値のない`return`文によって暗黙的な`undefined`を返すことを許可します。

## 正しい例

```js
/* eslint getter-return: ["error"] */

let obj = {
  get a() {
    return 1;
  }
};

Object.defineProperty(obj, "b", {
    get: function (){
        return 2;
    }
});

class C {
    get c(){
        return 3;
    }
}
```

```js
/* eslint getter-return: ["error", { "allowImplicit": true }] */

let obj = {
  get d() {
    return;
  }
};
```

## 間違いの例

```js
/* eslint getter-return: ["error"] */

let obj = {
  get e() {
  }
};
```

## コンフィグ

以下の設定で使用されています。

- eslint/recommended - `"error"`

## リンク

- [公式ドキュメント](https://eslint.org/docs/latest/rules/getter-return)
