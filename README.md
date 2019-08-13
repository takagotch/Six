### six
---
https://github.com/benjaminp/six

https://pypi.org/project/six/

```py
// test_six.py
import operator
import sys
import types
import unittest

import py

import six

def test_add_doc():
  def f():
    """ """
    pass
  six._add_doc(f, """New doc""")
  assert f.__doc__ == "New doc"
```

```
```

```
```


