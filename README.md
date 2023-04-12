# NLPImitation

I use dynamic arrays to make neural networks which can do NLP tasks. (refactoring...)

## Build

This project does not rely on any other third-party libraries.

Make sure you have `make`and `gcc` or `clang` in your environment. Then use this command:

```bash
make NLPImitation
```

Also can use `-j` to use multi-task of make.

## Future Work

This repo is too old and i'm trying to make it running correctly. (and only running this program takes lots of time...)

`nlpmain.cpp` and `mainassist.h` are useless. If you really want to use this project, only do this:

```C++
#include "src/NLPann.h"
```

Add the `NLPann.h` as the header, then you could use all models in it.
