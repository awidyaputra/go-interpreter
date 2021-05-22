# go-interpreter

# Interesting improvements
- Currently Monkey only supports ASCII. Change `bytes` to `runes` to support UTF-8 and Unicode
- Add `!` and `?` as identifiers. Sneak the logic in the lexer default branch.
- Add support for numbers outside of `int`. This includes `floats`, `hex`, `octal`.