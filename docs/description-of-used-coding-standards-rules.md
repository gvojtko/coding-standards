# Description of Used Coding Standards Rules

The tables below contain list of all coding standards rules that must be followed when using this package with default rulesets.
All the rules are checked automatically and can be also fixed automatically unless the last column (*Note*) states otherwise.

## Rules checked with [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

| Rule name                                     | Rule description                                                                                                                   | Note |
| --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---- |
| `@PSR2`                                       | See [official documentation](http://www.php-fig.org/psr/psr-2/).                                                                         |      |
| `array_syntax`                                | PHP arrays should be declared using short syntax.                                                                                  |      |
| `binary_operator_spaces`                      | All binary operators should be surrounded by one space. Double arrows nor equal signs are aligned.                                 |      |
| `blank_line_after_opening_tag`                | Ensure there is no code on the same line as the PHP open tag and it is followed by a blank line.                                   |      |
| `combine_consecutive_unsets`                  | Calling unset on multiple items should be done in one call.                                                                        |      |
| `concat_space`                                | Concatenation should be surrounded with one space.                                                                                 |      |
| `ereg_to_preg`                                | Replace deprecated `ereg` regular expression functions with `preg`.                                                                |      |
| `function_typehint_space`                     | Add missing space between function's argument and its typehint.                                                                    |      |
| `include`                                     | Include/Require and file path should be divided with a single space. File path should not be placed under brackets.                |      |
| `linebreak_after_opening_tag`                 | Ensure there is no code on the same line as the PHP open tag.                                                                      |      |
| `lowercase_cast`                              | Cast should be written in lower case.                                                                                              |      |
| `native_function_casing`                      | Function defined by PHP should be called using the correct casing.                                                                 |      |
| `new_with_braces`                             | All instances created with `new` keyword must be followed by braces.                                                               |      |
| `no_alias_functions`                          | Master functions shall be used instead of aliases.                                                                                 |      |
| `no_blank_lines_after_phpdoc`                 | There should not be blank lines between docblock and the documented element.                                                       |      |
| `no_empty_comment`                            | There should not be any empty comments.                                                                                            |      |
| `no_empty_phpdoc`                             | There should not be empty PHPDoc blocks.                                                                                           |      |
| `no_empty_statement`                          | Remove useless semicolon statements.                                                                                               |      |
| `no_extra_consecutive_blank_lines`            | Removes extra blank lines and blank lines in block of `use` statements.                                                            |      |
| `no_leading_import_slash`                     | Remove leading slashes in use clauses.                                                                                             |      |
| `no_leading_namespace_whitespace`             | The namespace declaration line should not contain leading whitespace.                                                              |      |
| `no_mixed_echo_print`                         | Only language construct `echo`, not `print` should be used.                                                                        |      |
| `no_multiline_whitespace_around_double_arrow` | Operator `=>` should not be surrounded by multi-line whitespaces.                                                                  |      |
| `no_multiline_whitespace_before_semicolons`   | Multi-line whitespace before closing semicolon are prohibited.                                                                     |      |
| `no_php4_constructor`                         | Convert PHP4-style constructors to `__construct`.                                                                                  |      |
| `no_short_bool_cast`                          | Short cast `bool` using double exclamation mark should not be used.                                                                |      |
| `no_singleline_whitespace_before_semicolons`  | Single-line whitespace before closing semicolon are prohibited.                                                                    |      |
| `no_spaces_around_offset`                     | There must not be spaces around offset braces.                                                                                     |      |
| `no_trailing_comma_in_list_call`              | Remove trailing commas in list function calls.                                                                                     |      |
| `no_trailing_comma_in_singleline_array`       | PHP single-line arrays should not have trailing comma.                                                                             |      |
| `no_unneeded_control_parentheses`             | Removes unneeded parentheses around control statements (`break`, `clone`, `continue`, `echo`, `print`, `switch`, `case`, `yield`). |      |
| `no_useless_return`                           | There should not be an empty return statement at the end of a function.                                                            |      |
| `no_whitespace_before_comma_in_array`         | In array declaration, there must not be a whitespace before each comma.                                                            |      |
| `no_whitespace_in_blank_line`                 | Remove trailing whitespace at the end of blank lines.                                                                              |      |
| `non_printable_character`                     | Remove Zero-width space (ZWSP), Non-breaking space (NBSP) and other invisible unicode symbols.                                     |      |
| `normalize_index_brace`                       | Array index should always be written by using square braces.                                                                       |      |
| `object_operator_without_whitespace`          | There should not be space before or after object `T_OBJECT_OPERATOR ->`.                                                           |      |
| `ordered_imports`                             | Use statements should be ordered alphabetically.                                                                                   |      |
| `phpdoc_annotation_without_dot`               | Phpdocs annotation descriptions should not be a sentence.                                                                          |      |
| `phpdoc_indent`                               | Docblocks should have the same indentation as the documented subject.                                                              |      |
| `phpdoc_no_useless_inheritdoc`                | Classes that does not inherit must not have inheritdoc tags.                                                                       |      |
| `phpdoc_no_access`                            | `@access` annotations should be omitted from phpdocs.                                                                              |      |
| `phpdoc_no_alias_tag`                         | PHPDoc alias `type` tag should not be used, it is replaced with `var`.                                                             |      |
| `phpdoc_no_empty_return`                      | `@return void` and `@return null` annotations should be omitted from phpdocs.                                                      |      |
| `phpdoc_no_package`                           | `@package` and `@subpackage` annotations should be omitted from phpdocs.                                                           |      |
| `phpdoc_order`                                | Annotations in phpdocs should be ordered so that param annotations come first, then throws annotations, then return annotations.   |      |
| `phpdoc_scalar`                               | Scalar types should always be written in the same form. `int` not `integer`, `bool` not `boolean`, `float` not `real` or `double`. |      |
| `phpdoc_single_line_var_spacing`              | Single line `@var` PHPDoc should have proper spacing.                                                                              |      |
| `phpdoc_trim`                                 | Phpdocs should start and end with content, excluding the very first and last line of the docblocks.                                |      |
| `phpdoc_var_without_name`                     | `@var` and `@type` annotations should not contain the variable name.                                                               |      |
| `protected_to_private`                        | Converts `protected` variables and methods to `private` where possible.                                                            |      |
| `self_accessor`                               | Inside a class element `self` should be preferred to the class name itself.                                                        |      |
| `semicolon_after_instruction`                 | Instructions must be terminated with a semicolon.                                                                                  |      |
| `short_scalar_cast`                           | Cast `(boolean)` and `(integer)` should be written as `(bool)` and `(int)`, `(double)` and `(real)` as `(float)`                   |      |
| `single_blank_line_before_namespace`          | There should be exactly one blank line before a namespace declaration.                                                             |      |
| `space_after_semicolon`                       | Fix whitespace after a semicolon.                                                                                                  |      |
| `single_quote`                                | Convert double quotes to single quotes for simple strings.                                                                         |      |
| `single_line_comment_style`                   | Single-line comments and multi-line comments with only one line of actual content should use the `//` syntax, not hash (`#`).      |      |
| `standardize_not_equals`                      | Replace all `<>` with `!=`.                                                                                                        |      |
| `strict_param`                                | Functions should be used with `$strict` param set to true.                                                                         |      |
| `ternary_operator_spaces`                     | Standardize spaces around ternary operator.                                                                                        |      |
| `trailing_comma_in_multiline_array`           | PHP multi-line arrays should have a trailing comma.                                                                                |      |
| `trim_array_spaces`                           | Arrays should be formatted like function/method arguments, without leading or trailing single line space.                          |      |
| `unary_operator_spaces`                       | Unary operators should be placed adjacent to their operands.                                                                       |      |
| `whitespace_after_comma_in_array`             | In array declaration, there must be a whitespace after each comma.                                                                 |      |
| `Shopsys/missing_button_type`                 | Adds mandatory `type` attribute to `<button>` HTML tag.                                                                            |      |
| `Shopsys/orm_join_column_require_nullable`    | Doctrine annotations `@ORM\ManyToOne` and `@ORM\OneToOne` must have defined `nullable` option in `@ORM\JoinColumn`.                |      |
| `Shopsys/no_unused_imports`                   | Unused use statements (except those from the same namespace) must be removed.                                                      |      |

## Rules checked with [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)

| Rule name                                          | Rule description                                                                                                                                                                                         | Note                                                           |
| ---------------------------------------------      | ----------------------------------------------------------------------------------------------------------------------------------                                                                       | ----                                                           |
| `Generic.Files.LineLength.TooLong`                 | Line length should not be longer than 80 characters. It must not be longer than 100 characters.                                                                                                          | Can not be fixed automatically. Ignored with default severity. |
| `Generic.CodeAnalysis.EmptyStatement`              | You should not use empty statements, only empty `catch` is allowed.                                                                                                                                      | Can not be fixed automatically.                                |
| `Generic.CodeAnalysis.ForLoopShouldBeWhileLoop`    | Detects for-loops that can be simplified to a while-loop.                                                                                                                                                | Can not be fixed automatically.                                |
| `Generic.CodeAnalysis.ForLoopWithTestFunctionCall` | Detects for-loops that use a function call in the test expression.                                                                                                                                       | Can not be fixed automatically.                                |
| `Generic.CodeAnalysis.JumbledIncrementer`          | Detects incrementer jumbling in for loops. Ie. the usage of one and the same incrementer into an inner and outer loop. Even it is intended this is confusing code.                                       | Can not be fixed automatically.                                |
| `Generic.CodeAnalysis.UnconditionalIfStatement`    | You should avoid `if` statements that are always `true` or `false`.                                                                                                                                      | Can not be fixed automatically.                                |
| `Generic.Commenting.Todo`                          | Warns about `TODO` comments.                                                                                                                                                                             | Can not be fixed automatically.                                |
| `Generic.Commenting.Fixme`                         | Warns about `FIXME` comments.                                                                                                                                                                            | Can not be fixed automatically.                                |
| `Generic.Formatting.NoSpaceAfterCast`              | Ensures there is no space after cast tokens.                                                                                                                                                             |                                                                |
| `Generic.Functions.CallTimePassByReference`        | Ensures that variables are not passed by reference when calling a function.                                                                                                                              | Can not be fixed automatically.                                |
| `Generic.NamingConventions.ConstructorName`        | Favor PHP 5 constructor syntax, which uses function `__construct()`. Avoid PHP 4 constructor syntax, which uses function `ClassName()`.                                                                  | Can not be fixed automatically.                                |
| `Generic.NamingConventions.CamelCapsFunctionName`  | Method names should be in camelCase (except for PHP magic methods and PHP non-magic methods starting with a double underscore).                                                                          | Can not be fixed automatically.                                |
| `Generic.PHP.NoSilencedErrors`                     | You should not use errors silencing using `@` sign.                                                                                                                                                      | Can not be fixed automatically.                                |
| `MySource.PHP.GetRequestData`                      | The request super globals (`$_REQUEST`, `$_GET`, `$_POST`, `$_FILES`) must not be accessed directly.                                                                                                     | Can not be fixed automatically.                                |
| `PEAR.Commenting.InlineComment`                    | Checks that no perl-style (starting with `#` symbol) comments are used.                                                                                                                                  |                                                                |
| `PEAR.NamingConventions.ValidClassName`            | Ensures class and interface names start with a capital letter.                                                                                                                                           | Can not be fixed automatically.                                |
| `Squiz.PHP.DisallowMultipleAssignments`            | Ensures that there is only one value assignment on a line, and that it is the first thing on the line.                                                                                                   | Can not be fixed automatically.                                |
| `Squiz.PHP.DisallowSizeFunctionsInLoop`            | Bans the use of size-based functions (`sizeof`, `strlen`, `count`) in loop conditions.                                                                                                                   | Can not be fixed automatically.                                |
| `Squiz.PHP.Eval`                                   | The use of `eval()` is discouraged.                                                                                                                                                                      | Can not be fixed automatically.                                |
| `Squiz.PHP.GlobalKeyword`                          | The usage of the `global` keyword is discouraged.                                                                                                                                                        | Can not be fixed automatically.                                |
| `Squiz.PHP.InnerFunctions`                         | Ensures that functions within functions are never used.                                                                                                                                                  | Can not be fixed automatically.                                |
| `Squiz.PHP.LowercasePHPFunctions`                  | Ensures all calls to inbuilt PHP functions are lowercase.                                                                                                                                                |                                                                |
| `Squiz.PHP.NonExecutableCode`                      | Warns about code that can never been executed. This happens when a function returns before the code, or a break ends execution of a statement etc.                                                       | Can not be fixed automatically.                                |
| `Squiz.Scope.StaticThisUsage`                      | Checks for usage of `$this` in static methods, which would cause runtime errors.                                                                                                                         | Can not be fixed automatically.                                |
| `Squiz.Strings.DoubleQuoteUsage`                   | Makes sure that any use of double quotes is warranted.                                                                                                                                                   | Can not be fixed automatically.                                |
| `Squiz.WhiteSpace.CastSpacing`                     | Ensures cast statements do not contain whitespace.                                                                                                                                                       |                                                                |
| `Squiz.WhiteSpace.LanguageConstructSpacing`        | Ensures all language constructs (without brackets - `echo`, `print`, `return`, `include`, `include_once`, `require`, `require_once`, `new`) contain a single space between themselves and their content. |                                                                |
| `Squiz.WhiteSpace.LogicalOperatorSpacing`          | Verifies that operators have valid spacing (ie. one space) surrounding them.                                                                                                                             |                                                                |

## Rules checked with [PHPMD](https://github.com/phpmd/phpmd)

You can see [official documentation](https://phpmd.org/rules/index.html) for more information about the rules.

| Rule name                                           | Rule description                                                                                                                   | Note                                         |
| ---------------------------------------------       | ---------------------------------------------------------------------------------------------------------------------------------- | ----                                         |
| `rulesets/codesize.xml/CyclomaticComplexity`        | Cyclomatic complexity of a method must not be greater than 13.                                                                     | Can not be fixed automatically.              |
| `rulesets/codesize.xml/ExcessiveMethodLength`       | A method must not be longer than 51 lines.                                                                                         | Can not be fixed automatically.              |
| `rulesets/codesize.xml/ExcessiveClassLength`        | A class must not be longer than 501 lines.                                                                                         | Can not be fixed automatically.              |
| `rulesets/codesize.xml/ExcessivePublicCount`        | Amount of public methods and attributes in a class must not be greater than 31.                                                    | Can not be fixed automatically.              |
| `rulesets/controversial.xml/Superglobals`           | Super global variables must not be accessed directly.                                                                              | Can not be fixed automatically.              |
| `CamelCasePropertyName`                             | Property names must be in camelCase                                                                                                | Custom rule. Can not be fixed automatically. |
| `rulesets/controversial.xml/CamelCaseMethodName`    | Method names must be in camelCase                                                                                                  | Can not be fixed automatically.              |
| `rulesets/controversial.xml/CamelCaseParameterName` | Parameter names must be in camelCase                                                                                               | Can not be fixed automatically.              |
| `rulesets/controversial.xml/CamelCaseVariableName`  | Variable names must be in camelCase                                                                                                | Can not be fixed automatically.              |
| `rulesets/design.xml/ExitExpression`                | `exit` expression is not allowed.                                                                                                  | Can not be fixed automatically.              |
| `rulesets/design.xml/GotoStatement`                 | `goto` statement is not allowed.                                                                                                   | Can not be fixed automatically.              |
| `rulesets/naming.xml/ShortVariable`                 | Variable name must be at least 2 characters long.                                                                                  | Can not be fixed automatically.              |
| `rulesets/naming.xml/ShortMethodName`               | Method name must be at least 2 characters long.                                                                                    | Can not be fixed automatically.              |
| `rulesets/naming.xml/ConstantNamingConventions`     | Class/Interface constant names should always be defined in uppercase.                                                              | Can not be fixed automatically.              |
| `rulesets/unusedcode.xml/UnusedPrivateMethod`       | Code must not contain unused private methods.                                                                                      | Can not be fixed automatically.              |