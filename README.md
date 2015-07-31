README for LuaJIT 2.0.3
=======================

LuaJIT is a Just-In-Time (JIT) compiler for the Lua programming language.

Project Homepage: http://luajit.org/

LuaJIT is Copyright (C) 2005-2014 Mike Pall.
LuaJIT is free software, released under the MIT license.
See full Copyright Notice in the COPYRIGHT file or in luajit.h.

Documentation for LuaJIT is available in HTML format.
Please point your favorite browser to:

 doc/luajit.html


Custom Version Changes
----------------------

* Operation
 - A != B function like A ~= B
 - A && B  =>  A and B
 - A || B  =>  A or B
 - !A  =>  not A
 - A += B  =>  A = A + B
 - A -= B  =>  A = A - B
 - A *= B  =>  A = A * B
 - A /= B  =>  A = A / B
 - A %= B  =>  A = A % B

