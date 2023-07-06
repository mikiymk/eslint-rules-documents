# eslint rules

## Possible Problems 

- array-callback-return
- constructor-super
- for-direction
- getter-return
- no-async-promise-executor
- no-await-in-loop
- no-class-assign
- no-compare-neg-zero
- no-cond-assign
- no-const-assign
- no-constant-binary-expression

Disallow expressions where the operation doesn't affect the value

no-constant-condition
Disallow constant expressions in conditions

no-constructor-return
Disallow returning value from constructor

no-control-regex
Disallow control characters in regular expressions

no-debugger
Disallow the use of `debugger`

no-dupe-args
Disallow duplicate arguments in `function` definitions

no-dupe-class-members
Disallow duplicate class members

no-dupe-else-if
Disallow duplicate conditions in if-else-if chains

no-dupe-keys
Disallow duplicate keys in object literals

no-duplicate-case
Disallow duplicate case labels

no-duplicate-imports
Disallow duplicate module imports

no-empty-character-class
Disallow empty character classes in regular expressions

no-empty-pattern
Disallow empty destructuring patterns

no-ex-assign
Disallow reassigning exceptions in `catch` clauses

no-fallthrough
Disallow fallthrough of `case` statements

no-func-assign
Disallow reassigning `function` declarations

no-import-assign
Disallow assigning to imported bindings

no-inner-declarations
Disallow variable or `function` declarations in nested blocks

no-invalid-regexp
Disallow invalid regular expression strings in `RegExp` constructors

no-irregular-whitespace
Disallow irregular whitespace

no-loss-of-precision
Disallow literal numbers that lose precision

no-misleading-character-class
Disallow characters which are made with multiple code points in character class syntax

no-new-native-nonconstructor
Disallow `new` operators with global non-constructor functions

no-new-symbol
Disallow `new` operators with the `Symbol` object

no-obj-calls
Disallow calling global object properties as functions

no-promise-executor-return
Disallow returning values from Promise executor functions

no-prototype-builtins
Disallow calling some `Object.prototype` methods directly on objects

no-self-assign
Disallow assignments where both sides are exactly the same

no-self-compare
Disallow comparisons where both sides are exactly the same

no-setter-return
Disallow returning values from setters

no-sparse-arrays
Disallow sparse arrays

no-template-curly-in-string
Disallow template literal placeholder syntax in regular strings

no-this-before-super
Disallow `this`/`super` before calling `super()` in constructors

no-undef
Disallow the use of undeclared variables unless mentioned in `/*global */` comments

no-unexpected-multiline
Disallow confusing multiline expressions

no-unmodified-loop-condition
Disallow unmodified loop conditions

no-unreachable
Disallow unreachable code after `return`, `throw`, `continue`, and `break` statements

no-unreachable-loop
Disallow loops with a body that allows only one iteration

no-unsafe-finally
Disallow control flow statements in `finally` blocks

no-unsafe-negation
Disallow negating the left operand of relational operators

no-unsafe-optional-chaining
Disallow use of optional chaining in contexts where the `undefined` value is not allowed

no-unused-private-class-members
Disallow unused private class members

no-unused-vars
Disallow unused variables

no-use-before-define
Disallow the use of variables before they are defined

no-useless-backreference
Disallow useless backreferences in regular expressions

require-atomic-updates
Disallow assignments that can lead to race conditions due to usage of `await` or `yield`

use-isnan
Require calls to `isNaN()` when checking for `NaN`

valid-typeof
Enforce comparing `typeof` expressions against valid strings

Suggestions 

These rules suggest alternate ways of doing things:

accessor-pairs
Enforce getter and setter pairs in objects and classes

arrow-body-style
Require braces around arrow function bodies

block-scoped-var
Enforce the use of variables within the scope they are defined

camelcase
Enforce camelcase naming convention

capitalized-comments
Enforce or disallow capitalization of the first letter of a comment

class-methods-use-this
Enforce that class methods utilize `this`

complexity
Enforce a maximum cyclomatic complexity allowed in a program

consistent-return
Require `return` statements to either always or never specify values

consistent-this
Enforce consistent naming when capturing the current execution context

curly
Enforce consistent brace style for all control statements

default-case
Require `default` cases in `switch` statements

default-case-last
Enforce default clauses in switch statements to be last

default-param-last
Enforce default parameters to be last

dot-notation
Enforce dot notation whenever possible

eqeqeq
Require the use of `===` and `!==`

func-name-matching
Require function names to match the name of the variable or property to which they are assigned

func-names
Require or disallow named `function` expressions

func-style
Enforce the consistent use of either `function` declarations or expressions

grouped-accessor-pairs
Require grouped accessor pairs in object literals and classes

guard-for-in
Require `for-in` loops to include an `if` statement

id-denylist
Disallow specified identifiers

id-length
Enforce minimum and maximum identifier lengths

id-match
Require identifiers to match a specified regular expression

init-declarations
Require or disallow initialization in variable declarations

logical-assignment-operators
Require or disallow logical assignment operator shorthand

max-classes-per-file
Enforce a maximum number of classes per file

max-depth
Enforce a maximum depth that blocks can be nested

max-lines
Enforce a maximum number of lines per file

max-lines-per-function
Enforce a maximum number of lines of code in a function

max-nested-callbacks
Enforce a maximum depth that callbacks can be nested

max-params
Enforce a maximum number of parameters in function definitions

max-statements
Enforce a maximum number of statements allowed in function blocks

multiline-comment-style
Enforce a particular style for multiline comments

new-cap
Require constructor names to begin with a capital letter

no-alert
Disallow the use of `alert`, `confirm`, and `prompt`

no-array-constructor
Disallow `Array` constructors

no-bitwise
Disallow bitwise operators

no-caller
Disallow the use of `arguments.caller` or `arguments.callee`

no-case-declarations
Disallow lexical declarations in case clauses

no-confusing-arrow
Disallow arrow functions where they could be confused with comparisons

no-console
Disallow the use of `console`

no-continue
Disallow `continue` statements

no-delete-var
Disallow deleting variables

no-div-regex
Disallow equal signs explicitly at the beginning of regular expressions

no-else-return
Disallow `else` blocks after `return` statements in `if` statements

no-empty
Disallow empty block statements

no-empty-function
Disallow empty functions

no-empty-static-block
Disallow empty static blocks

no-eq-null
Disallow `null` comparisons without type-checking operators

no-eval
Disallow the use of `eval()`

no-extend-native
Disallow extending native types

no-extra-bind
Disallow unnecessary calls to `.bind()`

no-extra-boolean-cast
Disallow unnecessary boolean casts

no-extra-label
Disallow unnecessary labels

no-extra-semi
Disallow unnecessary semicolons

no-floating-decimal
Disallow leading or trailing decimal points in numeric literals

no-global-assign
Disallow assignments to native objects or read-only global variables

no-implicit-coercion
Disallow shorthand type conversions

no-implicit-globals
Disallow declarations in the global scope

no-implied-eval
Disallow the use of `eval()`-like methods

no-inline-comments
Disallow inline comments after code

no-invalid-this
Disallow use of `this` in contexts where the value of `this` is `undefined`

no-iterator
Disallow the use of the `__iterator__` property

no-label-var
Disallow labels that share a name with a variable

no-labels
Disallow labeled statements

no-lone-blocks
Disallow unnecessary nested blocks

no-lonely-if
Disallow `if` statements as the only statement in `else` blocks

no-loop-func
Disallow function declarations that contain unsafe references inside loop statements

no-magic-numbers
Disallow magic numbers

no-mixed-operators
Disallow mixed binary operators

no-multi-assign
Disallow use of chained assignment expressions

no-multi-str
Disallow multiline strings

no-negated-condition
Disallow negated conditions

no-nested-ternary
Disallow nested ternary expressions

no-new
Disallow `new` operators outside of assignments or comparisons

no-new-func
Disallow `new` operators with the `Function` object

no-new-object
Disallow `Object` constructors

no-new-wrappers
Disallow `new` operators with the `String`, `Number`, and `Boolean` objects

no-nonoctal-decimal-escape
Disallow `\8` and `\9` escape sequences in string literals

no-octal
Disallow octal literals

no-octal-escape
Disallow octal escape sequences in string literals

no-param-reassign
Disallow reassigning `function` parameters

no-plusplus
Disallow the unary operators `++` and `--`

no-proto
Disallow the use of the `__proto__` property

no-redeclare
Disallow variable redeclaration

no-regex-spaces
Disallow multiple spaces in regular expressions

no-restricted-exports
Disallow specified names in exports

no-restricted-globals
Disallow specified global variables

no-restricted-imports
Disallow specified modules when loaded by `import`

no-restricted-properties
Disallow certain properties on certain objects

no-restricted-syntax
Disallow specified syntax

no-return-assign
Disallow assignment operators in `return` statements

no-return-await
Disallow unnecessary `return await`

no-script-url
Disallow `javascript:` urls

no-sequences
Disallow comma operators

no-shadow
Disallow variable declarations from shadowing variables declared in the outer scope

no-shadow-restricted-names
Disallow identifiers from shadowing restricted names

no-ternary
Disallow ternary operators

no-throw-literal
Disallow throwing literals as exceptions

no-undef-init
Disallow initializing variables to `undefined`

no-undefined
Disallow the use of `undefined` as an identifier

no-underscore-dangle
Disallow dangling underscores in identifiers

no-unneeded-ternary
Disallow ternary operators when simpler alternatives exist

no-unused-expressions
Disallow unused expressions

no-unused-labels
Disallow unused labels

no-useless-call
Disallow unnecessary calls to `.call()` and `.apply()`

no-useless-catch
Disallow unnecessary `catch` clauses

no-useless-computed-key
Disallow unnecessary computed property keys in objects and classes

no-useless-concat
Disallow unnecessary concatenation of literals or template literals

no-useless-constructor
Disallow unnecessary constructors

no-useless-escape
Disallow unnecessary escape characters

no-useless-rename
Disallow renaming import, export, and destructured assignments to the same name

no-useless-return
Disallow redundant return statements

no-var
Require `let` or `const` instead of `var`

no-void
Disallow `void` operators

no-warning-comments
Disallow specified warning terms in comments

no-with
Disallow `with` statements

object-shorthand
Require or disallow method and property shorthand syntax for object literals

one-var
Enforce variables to be declared either together or separately in functions

one-var-declaration-per-line
Require or disallow newlines around variable declarations

operator-assignment
Require or disallow assignment operator shorthand where possible

prefer-arrow-callback
Require using arrow functions for callbacks

prefer-const
Require `const` declarations for variables that are never reassigned after declared

prefer-destructuring
Require destructuring from arrays and/or objects

prefer-exponentiation-operator
Disallow the use of `Math.pow` in favor of the `**` operator

prefer-named-capture-group
Enforce using named capture group in regular expression

prefer-numeric-literals
Disallow `parseInt()` and `Number.parseInt()` in favor of binary, octal, and hexadecimal literals

prefer-object-has-own
Disallow use of `Object.prototype.hasOwnProperty.call()` and prefer use of `Object.hasOwn()`

prefer-object-spread
Disallow using Object.assign with an object literal as the first argument and prefer the use of object spread instead

prefer-promise-reject-errors
Require using Error objects as Promise rejection reasons

prefer-regex-literals
Disallow use of the `RegExp` constructor in favor of regular expression literals

prefer-rest-params
Require rest parameters instead of `arguments`

prefer-spread
Require spread operators instead of `.apply()`

prefer-template
Require template literals instead of string concatenation

quote-props
Require quotes around object literal property names

radix
Enforce the consistent use of the radix argument when using `parseInt()`

require-await
Disallow async functions which have no `await` expression

require-unicode-regexp
Enforce the use of `u` flag on RegExp

require-yield
Require generator functions to contain `yield`

sort-imports
Enforce sorted import declarations within modules

sort-keys
Require object keys to be sorted

sort-vars
Require variables within the same declaration block to be sorted

spaced-comment
Enforce consistent spacing after the `//` or `/*` in a comment

strict
Require or disallow strict mode directives

symbol-description
Require symbol descriptions

vars-on-top
Require `var` declarations be placed at the top of their containing scope

yoda
Require or disallow "Yoda" conditions

Layout & Formatting 

These rules care about how the code looks rather than how it executes:

array-bracket-newline
Enforce linebreaks after opening and before closing array brackets

array-bracket-spacing
Enforce consistent spacing inside array brackets

array-element-newline
Enforce line breaks after each array element

arrow-parens
Require parentheses around arrow function arguments

arrow-spacing
Enforce consistent spacing before and after the arrow in arrow functions

block-spacing
Disallow or enforce spaces inside of blocks after opening block and before closing block

brace-style
Enforce consistent brace style for blocks

comma-dangle
Require or disallow trailing commas

comma-spacing
Enforce consistent spacing before and after commas

comma-style
Enforce consistent comma style

computed-property-spacing
Enforce consistent spacing inside computed property brackets

dot-location
Enforce consistent newlines before and after dots

eol-last
Require or disallow newline at the end of files

func-call-spacing
Require or disallow spacing between function identifiers and their invocations

function-call-argument-newline
Enforce line breaks between arguments of a function call

function-paren-newline
Enforce consistent line breaks inside function parentheses

generator-star-spacing
Enforce consistent spacing around `*` operators in generator functions

implicit-arrow-linebreak
Enforce the location of arrow function bodies

indent
Enforce consistent indentation

jsx-quotes
Enforce the consistent use of either double or single quotes in JSX attributes

key-spacing
Enforce consistent spacing between keys and values in object literal properties

keyword-spacing
Enforce consistent spacing before and after keywords

line-comment-position
Enforce position of line comments

linebreak-style
Enforce consistent linebreak style

lines-around-comment
Require empty lines around comments

lines-between-class-members
Require or disallow an empty line between class members

max-len
Enforce a maximum line length

max-statements-per-line
Enforce a maximum number of statements allowed per line

multiline-ternary
Enforce newlines between operands of ternary expressions

new-parens
Enforce or disallow parentheses when invoking a constructor with no arguments

newline-per-chained-call
Require a newline after each call in a method chain

no-extra-parens
Disallow unnecessary parentheses

no-mixed-spaces-and-tabs
Disallow mixed spaces and tabs for indentation

no-multi-spaces
Disallow multiple spaces

no-multiple-empty-lines
Disallow multiple empty lines

no-tabs
Disallow all tabs

no-trailing-spaces
Disallow trailing whitespace at the end of lines

no-whitespace-before-property
Disallow whitespace before properties

nonblock-statement-body-position
Enforce the location of single-line statements

object-curly-newline
Enforce consistent line breaks after opening and before closing braces

object-curly-spacing
Enforce consistent spacing inside braces

object-property-newline
Enforce placing object properties on separate lines

operator-linebreak
Enforce consistent linebreak style for operators

padded-blocks
Require or disallow padding within blocks

padding-line-between-statements
Require or disallow padding lines between statements

quotes
Enforce the consistent use of either backticks, double, or single quotes

rest-spread-spacing
Enforce spacing between rest and spread operators and their expressions

semi
Require or disallow semicolons instead of ASI

semi-spacing
Enforce consistent spacing before and after semicolons

semi-style
Enforce location of semicolons

space-before-blocks
Enforce consistent spacing before blocks

space-before-function-paren
Enforce consistent spacing before `function` definition opening parenthesis

space-in-parens
Enforce consistent spacing inside parentheses

space-infix-ops
Require spacing around infix operators

space-unary-ops
Enforce consistent spacing before or after unary operators

switch-colon-spacing
Enforce spacing around colons of switch statements

template-curly-spacing
Require or disallow spacing around embedded expressions of template strings

template-tag-spacing
Require or disallow spacing between template tags and their literals

unicode-bom
Require or disallow Unicode byte order mark (BOM)

wrap-iife
Require parentheses around immediate `function` invocations

wrap-regex
Require parenthesis around regex literals

yield-star-spacing
Require or disallow spacing around the `*` in `yield*` expressions


## Deprecated

callback-return deprecated
global-require deprecated
handle-callback-err deprecated
id-blacklist deprecated
indent-legacy deprecated
lines-around-directive deprecated
newline-after-var deprecated
newline-before-return deprecated
no-buffer-constructor deprecated
no-catch-shadow deprecated
no-mixed-requires deprecated
no-native-reassign deprecated
no-negated-in-lhs deprecated
no-new-require deprecated
no-path-concat deprecated
no-process-env deprecated
no-process-exit deprecated
no-restricted-modules deprecated
no-spaced-func deprecated
no-sync deprecated
prefer-reflect deprecated
require-jsdoc deprecated
valid-jsdoc deprecated

## Removed

generator-star removed
global-strict removed
no-arrow-condition removed
no-comma-dangle removed
no-empty-class removed
no-empty-label removed
no-extra-strict removed
no-reserved-keys removed
no-space-before-semi removed
no-wrap-func removed
space-after-function-name removed
space-after-keywords removed
space-before-function-parentheses removed
space-before-keywords removed
space-in-brackets removed
space-return-throw-case removed
space-unary-word-ops removed
spaced-line-comment removed
