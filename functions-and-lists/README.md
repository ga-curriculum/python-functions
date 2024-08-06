<h1>
  <span class="headline">Python Functions</span>
  <span class="subhead">Functions and Lists</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to use the `map()` function to apply a function to each item in a list and utilize `lambda` functions for concise, inline function definitions.

| Lesson            | Duration |
| ----------------- | -------- |
| Functions + Lists | 10 min   |

## Using `map()`

It’s common to want to apply a function to everything in a list. It’s actually so common that there’s a method to do exactly that: `map()`!

```python
greetings = ["hi", "hello", "salutations"]

def excitement(word):
    return word.upper() + "!!!"

excited_greetings = map(excitement, greetings)

# excited_greetings is ["HI!!!", "HELLO!!!", "SALUTATIONS!!!"]
```

## Lambda Functions

In this and in similar situations, you sometimes don’t even want to create a separate function to pass in.

You can define a **lambda** function directly in-line by using the `lambda` keyword and shortened definition syntax:

```python
greetings = ["hi", "hello", "salutations"]

excited_greetings = map(lambda word: word.upper() + "!!!", greetings)

# excited_greetings is ["HI!!!", "HELLO!!!", "SALUTATIONS!!!"]
```
