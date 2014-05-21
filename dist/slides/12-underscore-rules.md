##  Underscore Rules

What are the rules of underscores in numeric types?

note:
    * can’t start or end a literal value with an underscore.
    * can’t place an underscore right after the prefixes 0b, 0B, 0x, and 0X, which are used to define binary and hexadecimal literal values.
    * You can place an underscore right after the prefix 0, which is used to define an
    octal literal value.
    * You can’t place an underscore prior to an L suffix (the L suffix is used to mark a
    literal value as long).
    * You can’t use an underscore in positions where a string of digits is expected.
    * Java 7 Feature only
