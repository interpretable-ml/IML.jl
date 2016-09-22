# IML Julia

[![Build Status](https://travis-ci.org/interpretable-ml/iML.jl.svg?branch=master)](https://travis-ci.org/slundberg/iML.jl)

[![Coverage Status](https://coveralls.io/repos/interpretable-ml/iML.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/slundberg/iML.jl?branch=master)

[![codecov.io](http://codecov.io/github/interpretable-ml/iML.jl/coverage.svg?branch=master)](http://codecov.io/github/slundberg/iML.jl?branch=master)

This is a very thin wrapper around the code in the main `iml` project. It pulls the code in through [subtrees](https://git-scm.com/book/en/v2/Git-Tools-Advanced-Merging). To merge in the latest updates from the main project run:

```shell
git merge --squash -Xsubtree=iml iml
```
