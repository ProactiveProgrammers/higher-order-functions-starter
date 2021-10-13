# Higher-Order Functions

## Add Your Name Here

## Program Output

### What is the output from running the following commands?

TODO: Use a fenced code block to provide the output for this command.

- `python demonstrate-map-function.py`

### What is the output from running the following commands?

TODO: Use a fenced code block to provide the output for this command.

- `python demonstrate-reduce-function.py`

## Program Questions

### What is the purpose of the following source code statements?

```
def map(f, sequence):
    """Apply the function f to the sequence of values."""
    result = ()
    for element in sequence:
        result += ( f(element), )
    return result
```

TODO: Provide at least a one-paragraph response to this question.
TODO: Make sure that you write about each line in the program's source code.

### What is the purpose of the following source code statements?

```
def reduce(f, sequence, initial):
    """Starting at the value of initial, apply f to the sequence of values."""
    result = initial
    for value in sequence:
        result = f(result, value)
    return result
```

TODO: Provide at least a one-paragraph response to this question.
TODO: Make sure that you write about each line in the program's source code.

### As they are implemented in this project, why will `map` and `reduce` not reduce a program's running time?

TODO: Provide at least a one-paragraph response to this question.
