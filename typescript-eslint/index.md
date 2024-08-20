# typescript-eslint

- 🗃️ - オプションがある
- ⚙️ - 自動で修正ができる
- 💡 - 修正の提案ができる
- 📝 - `recommended`と`recommended-type-checked`のコンフィグで有効
- 🔒 - `strict`と`strict-type-checked`のコンフィグで有効
- 🎨 - `stylistic`と`stylistic-type-checked`のコンフィグで有効
- 🚨 - 型情報を使用する

## オリジナルルール

| ルール                                                                                          | 実装 | 🗃️  |  ⚙️  | 📝  | 🚨  |
| ----------------------------------------------------------------------------------------------- | ---- | :-: | :--: | :-: | :-: |
| [adjacent-overload-signatures](adjacent-overload-signatures.md)                                 |      |  -  |  -   | 🎨  |  -  |
| [array-type](array-type.md)                                                                     |      | 🗃️  |  ⚙️  | 🎨  |  -  |
| [await-thenable](await-thenable.md)                                                             |      |  -  |  💡  | 📝  |  -  |
| [ban-ts-comment](ban-ts-comment.md)                                                             |      | 🗃️  |  💡  | 📝  |  -  |
| [ban-tslint-comment](ban-tslint-comment.md)                                                     |      |  -  |  ⚙️  | 🎨  |  -  |
| [class-literal-property-style](class-literal-property-style.md)                                 |      | 🗃️  |  💡  | 🎨  |  -  |
| [consistent-generic-constructors](consistent-generic-constructors.md)                           |      | 🗃️  |  ⚙️  | 🎨  |  -  |
| [consistent-indexed-object-style](consistent-indexed-object-style.md)                           |      | 🗃️  |  ⚙️  | 🎨  |  -  |
| [consistent-type-assertions](consistent-type-assertions.md)                                     |      | 🗃️  | ⚙️💡 | 🎨  |  -  |
| [consistent-type-definitions](consistent-type-definitions.md)                                   |      | 🗃️  |  ⚙️  | 🎨  |  -  |
| [consistent-type-exports](consistent-type-exports.md)                                           |      | 🗃️  |  ⚙️  |  -  | 🚨  |
| [consistent-type-imports](consistent-type-imports.md)                                           |      | 🗃️  |  ⚙️  |  -  | 🚨  |
| [explicit-function-return-type](explicit-function-return-type.md)                               |      | 🗃️  |  -   |  -  |  -  |
| [explicit-member-accessibility](explicit-member-accessibility.md)                               |      | 🗃️  | ⚙️💡 |  -  |  -  |
| [explicit-module-boundary-types](explicit-module-boundary-types.md)                             |      | 🗃️  |  -   |  -  |  -  |
| [member-ordering](member-ordering.md)                                                           |      | 🗃️  |  -   |  -  |  -  |
| [method-signature-style](method-signature-style.md)                                             |      | 🗃️  |  ⚙️  |  -  |  -  |
| [naming-convention](naming-convention.md)                                                       |      | 🗃️  |  -   |  -  | 🚨  |
| [no-array-delete](no-array-delete.md)                                                           |      |  -  |  💡  | 📝  | 🚨  |
| [no-base-to-string](no-base-to-string.md)                                                       |      | 🗃️  |  -   | 📝  | 🚨  |
| [no-confusing-non-null-assertion](no-confusing-non-null-assertion.md)                           |      |  -  |  💡  | 🎨  |  -  |
| [no-confusing-void-expression](no-confusing-void-expression.md)                                 |      | 🗃️  | ⚙️💡 | 🔒  | 🚨  |
| [no-duplicate-enum-values](no-duplicate-enum-values.md)                                         |      |  -  |  -   | 📝  |  -  |
| [no-duplicate-type-constituents](no-duplicate-type-constituents.md)                             |      | 🗃️  |  ⚙️  | 📝  | 🚨  |
| [no-dynamic-delete](no-dynamic-delete.md)                                                       |      |  -  |  ⚙️  | 🔒  |  -  |
| [no-empty-object-type](no-empty-object-type.md)                                                 |      | 🗃️  |  💡  | 📝  |  -  |
| [no-explicit-any](no-explicit-any.md)                                                           |      | 🗃️  | ⚙️💡 | 📝  |  -  |
| [no-extra-non-null-assertion](no-extra-non-null-assertion.md)                                   |      |  -  |  ⚙️  | 📝  |  -  |
| [no-extraneous-class](no-extraneous-class.md)                                                   |      | 🗃️  |  -   | 🔒  |  -  |
| [no-floating-promises](no-floating-promises.md)                                                 |      | 🗃️  |  💡  | 📝  | 🚨  |
| [no-for-in-array](no-for-in-array.md)                                                           |      |  -  |  -   | 📝  | 🚨  |
| [no-import-type-side-effects](no-import-type-side-effects.md)                                   |      |  -  |  ⚙️  |  -  |  -  |
| [no-inferrable-types](no-inferrable-types.md)                                                   |      | 🗃️  |  ⚙️  | 🎨  |  -  |
| [no-invalid-void-type](no-invalid-void-type.md)                                                 |      | 🗃️  |  -   | 🔒  |  -  |
| [no-meaningless-void-operator](no-meaningless-void-operator.md)                                 |      | 🗃️  | ⚙️💡 | 🔒  | 🚨  |
| [no-misused-new](no-misused-new.md)                                                             |      |  -  |  -   | 📝  |  -  |
| [no-misused-promises](no-misused-promises.md)                                                   |      | 🗃️  |  -   | 📝  | 🚨  |
| [no-mixed-enums](no-mixed-enums.md)                                                             |      |  -  |  -   | 🔒  | 🚨  |
| [no-namespace](no-namespace.md)                                                                 |      | 🗃️  |  -   | 📝  |  -  |
| [no-non-null-asserted-nullish-coalescing](no-non-null-asserted-nullish-coalescing.md)           |      |  -  |  💡  | 🔒  |  -  |
| [no-non-null-asserted-optional-chain](no-non-null-asserted-optional-chain.md)                   |      |  -  |  💡  | 📝  |  -  |
| [no-non-null-assertion](no-non-null-assertion.md)                                               |      |  -  |  💡  | 🔒  |  -  |
| [no-redundant-type-constituents](no-redundant-type-constituents.md)                             |      |  -  |  -   | 📝  | 🚨  |
| [no-require-imports](no-require-imports.md)                                                     |      | 🗃️  |  -   | 📝  |  -  |
| [no-restricted-types](no-restricted-types.md)                                                   |      | 🗃️  | ⚙️💡 |  -  |  -  |
| [no-this-alias](no-this-alias.md)                                                               |      | 🗃️  |  -   | 📝  |  -  |
| [no-unnecessary-boolean-literal-compare](no-unnecessary-boolean-literal-compare.md)             |      | 🗃️  |  ⚙️  | 🔒  | 🚨  |
| [no-unnecessary-condition](no-unnecessary-condition.md)                                         |      | 🗃️  |  ⚙️  | 🔒  | 🚨  |
| [no-unnecessary-parameter-property-assignment](no-unnecessary-parameter-property-assignment.md) |      |  -  |  -   |  -  |  -  |
| [no-unnecessary-qualifier](no-unnecessary-qualifier.md)                                         |      |  -  |  ⚙️  |  -  | 🚨  |
| [no-unnecessary-template-expression](no-unnecessary-template-expression.md)                     |      |  -  |  ⚙️  | 🔒  | 🚨  |
| [no-unnecessary-type-arguments](no-unnecessary-type-arguments.md)                               |      |  -  |  ⚙️  | 🔒  | 🚨  |
| [no-unnecessary-type-assertion](no-unnecessary-type-assertion.md)                               |      | 🗃️  |  ⚙️  | 📝  | 🚨  |
| [no-unnecessary-type-constraint](no-unnecessary-type-constraint.md)                             |      |  -  |  💡  | 📝  |  -  |
| [no-unnecessary-type-parameters](no-unnecessary-type-parameters.md)                             |      |  -  |  -   | 🔒  | 🚨  |
| [no-unsafe-argument](no-unsafe-argument.md)                                                     |      |  -  |  -   | 📝  | 🚨  |
| [no-unsafe-assignment](no-unsafe-assignment.md)                                                 |      |  -  |  -   | 📝  | 🚨  |
| [no-unsafe-call](no-unsafe-call.md)                                                             |      |  -  |  -   | 📝  | 🚨  |
| [no-unsafe-declaration-merging](no-unsafe-declaration-merging.md)                               |      |  -  |  -   | 📝  |  -  |
| [no-unsafe-enum-comparison](no-unsafe-enum-comparison.md)                                       |      |  -  |  💡  | 📝  | 🚨  |
| [no-unsafe-function-type](no-unsafe-function-type.md)                                           |      |  -  |  ⚙️  | 📝  |  -  |
| [no-unsafe-member-access](no-unsafe-member-access.md)                                           |      |  -  |  -   | 📝  | 🚨  |
| [no-unsafe-return](no-unsafe-return.md)                                                         |      |  -  |  -   | 📝  | 🚨  |
| [no-unsafe-unary-minus](no-unsafe-unary-minus.md)                                               |      |  -  |  -   | 📝  | 🚨  |
| [no-useless-empty-export](no-useless-empty-export.md)                                           |      |  -  |  ⚙️  |  -  |  -  |
| [no-wrapper-object-types](no-wrapper-object-types.md)                                           |      |  -  |  ⚙️  | 📝  |  -  |
| [non-nullable-type-assertion-style](non-nullable-type-assertion-style.md)                       |      |  -  |  ⚙️  | 🎨  | 🚨  |
| [parameter-properties](parameter-properties.md)                                                 |      | 🗃️  |  -   |  -  |  -  |
| [prefer-as-const](prefer-as-const.md)                                                           |      |  -  | ⚙️💡 | 📝  |  -  |
| [prefer-enum-initializers](prefer-enum-initializers.md)                                         |      |  -  |  💡  |  -  |  -  |
| [prefer-find](prefer-find.md)                                                                   |      |  -  |  💡  | 🎨  | 🚨  |
| [prefer-for-of](prefer-for-of.md)                                                               |      |  -  |  -   | 🎨  |  -  |
| [prefer-function-type](prefer-function-type.md)                                                 |      |  -  |  ⚙️  | 🎨  |  -  |
| [prefer-includes](prefer-includes.md)                                                           |      |  -  |  ⚙️  | 🎨  | 🚨  |
| [prefer-literal-enum-member](prefer-literal-enum-member.md)                                     |      | 🗃️  |  -   | 🔒  |  -  |
| [prefer-namespace-keyword](prefer-namespace-keyword.md)                                         |      |  -  |  ⚙️  | 📝  |  -  |
| [prefer-nullish-coalescing](prefer-nullish-coalescing.md)                                       |      | 🗃️  |  💡  | 🎨  | 🚨  |
| [prefer-optional-chain](prefer-optional-chain.md)                                               |      | 🗃️  | ⚙️💡 | 🎨  | 🚨  |
| [prefer-readonly](prefer-readonly.md)                                                           |      | 🗃️  |  ⚙️  |  -  | 🚨  |
| [prefer-readonly-parameter-types](prefer-readonly-parameter-types.md)                           |      | 🗃️  |  -   |  -  | 🚨  |
| [prefer-reduce-type-parameter](prefer-reduce-type-parameter.md)                                 |      |  -  |  ⚙️  | 🔒  | 🚨  |
| [prefer-regexp-exec](prefer-regexp-exec.md)                                                     |      |  -  |  ⚙️  | 🎨  | 🚨  |
| [prefer-return-this-type](prefer-return-this-type.md)                                           |      |  -  |  ⚙️  | 🔒  | 🚨  |
| [prefer-string-starts-ends-with](prefer-string-starts-ends-with.md)                             |      | 🗃️  |  ⚙️  | 🎨  | 🚨  |
| [promise-function-async](promise-function-async.md)                                             |      | 🗃️  |  ⚙️  |  -  | 🚨  |
| [require-array-sort-compare](require-array-sort-compare.md)                                     |      | 🗃️  |  -   |  -  | 🚨  |
| [restrict-plus-operands](restrict-plus-operands.md)                                             |      | 🗃️  |  -   | 📝  | 🚨  |
| [restrict-template-expressions](restrict-template-expressions.md)                               |      | 🗃️  |  -   | 📝  | 🚨  |
| [strict-boolean-expressions](strict-boolean-expressions.md)                                     |      | 🗃️  | ⚙️💡 |  -  | 🚨  |
| [switch-exhaustiveness-check](switch-exhaustiveness-check.md)                                   |      | 🗃️  |  💡  |  -  | 🚨  |
| [triple-slash-reference](triple-slash-reference.md)                                             |      | 🗃️  |  -   | 📝  |  -  |
| [typedef](typedef.md)                                                                           |      | 🗃️  |  -   |  -  |  -  |
| [unbound-method](unbound-method.md)                                                             |      | 🗃️  |  -   | 📝  | 🚨  |
| [unified-signatures](unified-signatures.md)                                                     |      | 🗃️  |  -   | 🔒  |  -  |
| [use-unknown-in-catch-callback-variable](use-unknown-in-catch-callback-variable.md)             |      |  -  | ⚙️💡 | 🔒  | 🚨  |

## ESLint のルールを拡張したもの

| ルール                                                          | 元ルール                                                                  | 実装 | 🗃️  |  ⚙️  | 📝  | 🚨  |
| --------------------------------------------------------------- | ------------------------------------------------------------------------- | ---- | :-: | :--: | :-: | :-: |
| [class-methods-use-this](class-methods-use-this.md)             | [class-methods-use-this](../eslint/class-methods-use-this.md)             |      | 🗃️  |  -   |  -  |  -  |
| [consistent-return](consistent-return.md)                       | [consistent-return](../eslint/consistent-return.md)                       |      | 🗃️  |  -   |  -  | 🚨  |
| [default-param-last](default-param-last.md)                     | [default-param-last](../eslint/default-param-last.md)                     |      | 🗃️  |  -   |  -  |  -  |
| [dot-notation](dot-notation.md)                                 | [dot-notation](../eslint/dot-notation.md)                                 |      | 🗃️  |  ⚙️  | 🎨  | 🚨  |
| [init-declarations](init-declarations.md)                       | [init-declarations](../eslint/init-declarations.md)                       |      | 🗃️  |  -   |  -  |  -  |
| [max-params](max-params.md)                                     | [max-params](../eslint/max-params.md)                                     |      | 🗃️  |  -   |  -  |  -  |
| [no-array-constructor](no-array-constructor.md)                 | [no-array-constructor](../eslint/no-array-constructor.md)                 |      |  -  |  ⚙️  | 📝  |  -  |
| [no-dupe-class-members](no-dupe-class-members.md)               | [no-dupe-class-members](../eslint/no-dupe-class-members.md)               |      |  -  |  -   |  -  |  -  |
| [no-empty-function](no-empty-function.md)                       | [no-empty-function](../eslint/no-empty-function.md)                       |      | 🗃️  |  -   | 🎨  |  -  |
| [no-implied-eval](no-implied-eval.md)                           | [no-implied-eval](../eslint/no-implied-eval.md)                           |      |  -  |  -   | 📝  | 🚨  |
| [no-invalid-this](no-invalid-this.md)                           | [no-invalid-this](../eslint/no-invalid-this.md)                           |      | 🗃️  |  -   |  -  |  -  |
| [no-loop-func](no-loop-func.md)                                 | [no-loop-func](../eslint/no-loop-func.md)                                 |      |  -  |  -   |  -  |  -  |
| [no-magic-numbers](no-magic-numbers.md)                         | [no-magic-numbers](../eslint/no-magic-numbers.md)                         |      | 🗃️  |  -   |  -  |  -  |
| [no-redeclare](no-redeclare.md)                                 | [no-redeclare](../eslint/no-redeclare.md)                                 |      | 🗃️  |  -   |  -  |  -  |
| [no-restricted-imports](no-restricted-imports.md)               | [no-restricted-imports](../eslint/no-restricted-imports.md)               |      | 🗃️  |  -   |  -  |  -  |
| [no-shadow](no-shadow.md)                                       | [no-shadow](../eslint/no-shadow.md)                                       |      | 🗃️  |  -   |  -  |  -  |
| [no-unused-expressions](no-unused-expressions.md)               | [no-unused-expressions](../eslint/no-unused-expressions.md)               |      | 🗃️  |  -   | 📝  |  -  |
| [no-unused-vars](no-unused-vars.md)                             | [no-unused-vars](../eslint/no-unused-vars.md)                             |      | 🗃️  |  -   | 📝  |  -  |
| [no-use-before-define](no-use-before-define.md)                 | [no-use-before-define](../eslint/no-use-before-define.md)                 |      | 🗃️  |  -   |  -  |  -  |
| [no-useless-constructor](no-useless-constructor.md)             | [no-useless-constructor](../eslint/no-useless-constructor.md)             |      |  -  |  -   | 🔒  |  -  |
| [only-throw-error](only-throw-error.md)                         | [no-throw-literal](../eslint/no-throw-literal.md)                         |      | 🗃️  |  -   | 📝  | 🚨  |
| [prefer-destructuring](prefer-destructuring.md)                 | [prefer-destructuring](../eslint/prefer-destructuring.md)                 |      | 🗃️  |  ⚙️  |  -  | 🚨  |
| [prefer-promise-reject-errors](prefer-promise-reject-errors.md) | [prefer-promise-reject-errors](../eslint/prefer-promise-reject-errors.md) |      | 🗃️  |  -   | 📝  | 🚨  |
| [require-await](require-await.md)                               | [require-await](../eslint/require-await.md)                               |      |  -  |  💡  | 📝  | 🚨  |
| [return-await](return-await.md)                                 | [no-return-await](../eslint/no-return-await.md)                           |      | 🗃️  | ⚙️💡 | 📝  | 🚨  |
