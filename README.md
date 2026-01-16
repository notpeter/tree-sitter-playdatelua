# tree-sitter-lua-playdate

Lua grammar for tree-sitter.

Fork of [tree-sitter-grammars/tree-sitter-lua](https://github.com/tree-sitter-grammars/tree-sitter-lua) adding
[Compound Assignment Operators](https://sdk.play.date/3.0.2/Inside%20Playdate.html#additional-assignment-operators)
as used in the Panic Playdate SDK version of Lua.

| Op  | Name                      |
| --- | ------------------------- |
| +=  | Addition                  |
| -=  | Subtraction               |
| \*= | Multiplication            |
| /=  | Division                  |
| //= | Integer division          |
| %=  | Modulo                    |
| <<= | Shift left                |
| >>= | Shift right               |
| &=  | Bitwise AND               |
| \|= | Bitwise OR                |
| ^=  | Exponent (not bitwise XOR |

See [LuaPowerPatches on lua-users.org wiki](http://lua-users.org/wiki/LuaPowerPatches) for more info.
The original link to the patch there is broken, but is available here: [plusequals-5.4.0-beta.patch](https://github.com/notpeter/playdate-lua/blob/main/patch/plusequals-5.4.0-beta.patch).

## See also:

- [Zed Playdate Extension](https://github.com/notpeter/playdate-zed-extension)
