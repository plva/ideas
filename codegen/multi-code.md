# Info
We allow multiple code types and DSLs in the same code file.

We define function templates, and use these functions with parameters to create the final code functions.

```python
class FooEntityDao:
    FooDao fooDao = FooDaoFactory.getFooInstance()
    function getFoo(baz):
        fooDao.getFooByBaz(baz)

```    
