# bfe

_sample_

```python
>>> supported_platforms = ['nexus', 'catalyst']
>>>
>>> for platform in platforms:
...     if platform in supported_platforms:
...         print("Platform {}  -- SUPPORTED".format(platform))
...
...
Platform nexus  -- SUPPORTED
Platform catalyst  -- SUPPORTED
>>>
```
***test***

ALWAYS, if a dictionary key may not exist, do NOT use the notation like `dict['key']`.  Instead, you should use `dict.get('key')`
