
## Special Parameters

### Syntax:

```py
def f(pos1, pos2, /, pos_or_kwd, *, kwd1, kwd2):
      -----------    ----------     ----------
        |             |                  |
        |        Positional or keyword   |
        |                                - Keyword only
         -- Positional only
```

- / and * are optional

Reference:

- [Special Parameters](https://docs.python.org/3/tutorial/controlflow.html#special-parameters)
