In most programming languages, loop control statements like `break` and `continue` only affect the innermost loop they are in. Consider the pseudocode below as an example:

```
list1 = ['a', 'b', 'c']
list2 = [1, 2, 3, 4, 5]

FOR each item1 IN list1:
    FOR each item2 IN list2:
        IF item2 > 2:
            BREAK
        PRINT item1, item2
```

In this example the output will be:

```
a 1
a 2
b 1
b 2
c 1
c 2
```

When the inner loop encounters a value greater than 2, it breaks out of itself and the outer loop proceeds to the next item in `list1`.
