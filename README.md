# MiniScript

This project contains the source code of both C# and C++ implementations of the [MiniScript scripting language](http://miniscript.org).



## Sponsor Me!

MiniScript is free, and apart from a small amount of revenue from the [books](https://miniscript.org/books/) and [Unity asset](https://assetstore.unity.com/packages/tools/integration/miniscript-87926), generates no significant income.  Your support is greatly appreciated, and will be used to fund community growth & reward programs like [these](https://miniscript.org/earn.html).

So, [click here to sponsor](https://github.com/sponsors/JoeStrout) -- contributions of any size are greatly appreciated!


# Changes

## import intrinsic (in c# part)

Vm has a List<string> named PossibleLibFolders where we can specify folder where to look for the imported files. Import expect one filepath parameter which can be relative also, this path will be searched in PossibleLibFolders. 