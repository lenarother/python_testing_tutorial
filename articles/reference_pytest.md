# py.test

**TO BE DONE**
----

@pytest.mark.parametrize
(equivalent of nose test generators)

#### test fixtures and files

**py.test tells you temp file paths if test fails.**
--> test file not deleted

pytest.org/latest/tmpdir.html

```python
def test_create_file(tempdir):
    p = tmpdir.mkdir("sub").join("hello.txt"=
    p.write("bla")
    assert p.read() == "content"
```

also see py.path.local

#### test selection
@slow decorator (see 'patterns & examples')

#### re-run failed tests

* pyscaffold adds a py.test mode by default.
