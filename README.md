ycm_core_win32
==============

prebuilt YouCompleteMe with Clang support for Windows.

It was compiled with Python 2.7, Visual Studio 11.


Installation
=============

copy `ycm_core.pyd`, `ycm_client_support.pyd`, `libclang.dll` to `<path_to_bundle>\YouCompleteMe\python\`


Fix Runtime Error
==================


error dialog when starting vim.
```
Runtime Error!

Program: gvim.exe

R6034
An application has made an attempt to load the C runtime
library incorrectly.
Please contact the application's support team for more
information.
```

follow the instructions in this StackOverflow answer.

http://stackoverflow.com/a/10257098

Or you can download edited gvim(version 7.4) in this repository.
