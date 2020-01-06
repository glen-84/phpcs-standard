# PHPCS standard

A PSR-12 compliant coding standard for PHP.

## Development

Run `composer install` to install the project dependencies.

## Unused rules

### Has issues

* `Generic.Commenting.DocComment.ContentAfterOpen` and `Generic.Commenting.DocComment.ContentBeforeClose`
    * https://github.com/squizlabs/PHP_CodeSniffer/issues/258

### No use for

* `Generic.Formatting.SpaceBeforeCast` – don't want space before casts inside parentheses (function calls, etc.).
* `Squiz.WhiteSpace.MemberVarSpacing` – don't want to require blank lines between class fields.
