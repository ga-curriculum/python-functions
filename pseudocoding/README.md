<h1>
  <span class="headline">Python Functions</span>
  <span class="subhead">Pseudocoding</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to break down complex processes into pseudocode, which will help them understand how to structure their code and identify the steps needed for function implementation.

| Lesson       | Duration |
| ------------ | -------- |
| Pseudocoding | 40 min   |

## The Good News About Computers

> "The good news about computers is that they do what you tell them to do. The bad news is that they do what you tell them to do."
> — Ted Nelson, technology pioneer

<!-- ![Image Placeholder](TKTK) -->

Now that we’ve learned how to write functions, we can consider more complex problems for our programs to tackle.
This will require thinking critically about the individual steps involved in any process we want to represent with a function.

## Thinking Like a Computer

The art of programming requires understanding how a computer thinks:

| **A Computer**                                                |                                                                                   |
| ------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| It only knows what you tell it...                             | ...but it will remember what it’s been told.                                      |
| It only understands a very limited set of phrases (syntax)... | ...but you can teach it a lot by combining these basic phrases together.          |
| It will always do what you say...                             | ...but not necessarily what you meant.                                            |
| It has no understanding of context...                         | ...but it’s not shy about saying when it doesn’t understand you (error messages). |

## Using Pseudocode

**Pseudocode** uses the structure of code without having to worry about the actual coding language (syntax) of the instructions.

Pseudocode is an attempt to break down a larger process into the smallest imaginable component steps.

<!-- ![Image Placeholder](TKTK) -->

> 💡 Pseudocode both helps us think like the computer AND creates easily achieved and testable milestones while coding. Once we have our process defined and broken down into small steps, finding the right syntax and implementation of each step is much easier.

## A Stir Fry Program

```python
spices = soy_sauce + rice_vinegar + sugar
oil = 1.5 ounces
brown_rice = 1.5 cups
broccoli = 2 cups
shrimp = .5 pounds
```

```python
stir_fry():
    cook brown_rice
    whisk spices
    heat oil in pan
    add broccoli
    cook shrimp
    add spices
```

- Think of writing functions like _following a recipe_. This makes the process more relatable and easier to understand.

- Programming can be viewed as something familiar by comparing it to everyday tasks, helping you grasp the concept better.

- Consider how a computer might misinterpret instructions. For example, how does it understand actions like "cook" or "whisk" in pseudocode?

- Start with defining basic functions and gradually build up to more complex ones, just as you would with simple tasks leading to more sophisticated ones.

## A Stir Fry Program With Parameters

The ingredients act as `variables` being passed into the `stir_fry()` function.

```python
spices = soy_sauce + rice_vinegar + sugar
oil = 1.5 ounces
brown_rice = 1.5 cups
broccoli = 2 cups
shrimp = .5 pounds
```

Recipe verbs are `functions` you
can use with the ingredient variables.

```python
stir_fry(item1, item2, item3, item4, item5):
    cook(item1)
    whisk(item2, item3)
    heat(item3)
    combine(item3, item4)
    cook(item5)
    add(item2)

stir_fry(brown_rice, spices, oil, broccoli, shrimp)
```

- By creating a `stir_fry()` function and passing it ingredients and ordered steps of additional supporting functions, we’ve created a program that is reusable. This reusability is dependent on passing in a standard input (ingredients in the same order), which then will return a standard output (a consistent meal).

> 💡 Using functions is vital to controlling complexity creep. Without smaller functions to package our reusable pieces of logic, our programs might contain hundreds of the tiniest, seemingly unconnected steps spilled out in a row. At the lowest level, any instructions would be absurdly difficult to piece together without larger abstracted bits of logic.

> Programs don’t get more complicated because of code. They get more complicated because of the logic behind them.

<br>

<div class="activity discussion">
  <h2 class="title">Pseudocoding a Process</h2>
  <span class="minutes">5 min</span>
</div>

Think about a process that you’re required to perform in your role. How you would pseudocode instructions for a new employee?

- What inputs are required to perform the process?
- What are the concrete steps involved?
- What is the output of that process, if any?

Complete this activity as a group using one or two examples suggested by the class. You can write the steps down to keep track of them as you go.

<br>

<div class="activity partner-exercise">
  <h2 class="title">5.2 Problem-Solving Functions</h2>
  <span class="minutes">30 min</span>
</div>

The next few functions will require a bit of problem-solving logic to produce a specific result from given inputs. Pseudocoding may help you by writing out the steps before coding them!

<!-- ![Image Placeholder](TKTK) -->

> Figuring out the steps is the hard part; writing the actual code behind the function is much easier once the steps have been determined.
