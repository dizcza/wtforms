### Actual Behavior

```python
# Paste a minimal piece of code that causes the problem. Here is an example:

>>> import wtforms
>>> class F(wtforms.Form):
...     foo = wtforms.StringField()
>>> f = F(foo="bar")
>>> print(f.foo.shrug)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'StringField' object has no attribute 'shrug'
```

### Expected Behavior

```python
# Show us, and explain what behavior you would have expected.
# Here is an example:

>>> import wtforms
>>> class F(wtforms.Form):
...     foo = wtforms.StringField()
>>> f = F(foo="bar")
>>> print(f.foo.shrug)
¯\_(ツ)_/¯
```

### Environment

* Python version:
* wtforms version:
