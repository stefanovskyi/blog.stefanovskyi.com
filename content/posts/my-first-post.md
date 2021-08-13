---
title: "My First Post"
date: 2021-08-13T21:31:51+03:00
draft: false
---

Hi everyone, this is my first post

Code sample in python
```python
from pytest_perf.deco import extras


@extras('perf')
def discovery_perf():
    "discovery"
    import importlib_metadata  # end warmup

    importlib_metadata.distribution('ipython')
```

image test

![alt text](https://www.gravatar.com/avatar/e5c5dd043eb3a8c0b3639fd41844d30e?s=64&d=identicon&r=PG)