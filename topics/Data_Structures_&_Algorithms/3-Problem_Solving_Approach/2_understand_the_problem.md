## [Topics](../../../topics.md)/[Data Structure & Algorithms](../index.md)/[Problem Solving Approach](./index.md)

# Understand The Problem

One of the biggest challenges for new developers has to do with solving problems. It's something that you get better at with time, but it definitely helps to have a strong problem-solving mindset.

To aid in the understanding of our problem, we can ask some very deliberate questions:

- Can I restate the problem in my own words?
- What are the inputs that go into the problem?
- What are the outputs that should come from the solution to the problem?
- Can the outputs be determined from the inputs? In other words, do I have enough information to solve the problem? (Keep in mind that this may not be answerable at the beginning, but it's still useful to consider)
- How should I label the important pieces of data that are a part of the problem?

Let's use a simple example to highlight this:

- #### Write a function which takes two numbers and returns their sum.

_Can I restate the problem in my own words?_

"Write a function that adds 2 numbers"

_What are the inputs that go into the problem?_

> For the sake of the question, it seems like an easy response, but it really isn't due to constraints placed by languages. Do we want 2 integers? 2 floats? What do we do if it's really large numbers past the upper bound that JavaScript allows? This may seem like over-complicating the question, but this shows how to start planning for edge cases etc.
> For the sake of this, let's say the answer is:

"Two Integers"

_What are the outputs that should come from the solution to the problem?_

> We can place the same questions as with the input question, so let's just say for simplicity's sake that the answer is:

"One Integer"

_Can the outputs be determined from the inputs?_

> This depends on any restrictions put on the question itself, so keep that in mind.

_How should I label the important pieces of data that are a part of the problem?_

```
function createSum(num1, num2) {
    let sum = num1 + num2;
    return sum;
}
```

"As shown above, we use `num1` and `num2` for our input, and `sum` for our output."

