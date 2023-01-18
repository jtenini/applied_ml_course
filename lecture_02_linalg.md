# Linear Algebra for Machine Learning

For this lecture, we will follow these [notes](https://medium.com/rv-data/linear-algebra-for-machine-learning-bed3d0b86d3) to introduce the core concepts from linear algebra that are commonly used in machine learning.

## Notation

### Common fields

I will generally use k for an arbitrary field, but there are some fields that come up so often that they get special treatment. In most documents, they are written with “blackboard” styling:
- \mathbb{Q}: The field of rational numbers — the set of numbers that can be represented as \frac{a}{b} where $a$ and $b$ are integers.
- \mathbb{R}: The field of real numbers.
- \mathbb{C}: The field of complex numbers — the set of numbers of the form $a + bi$ where $a$ and $b$ are integers.

So . . . what’s a field? A field is just a set with an addition and multiplication operation that are well behaved. In particular, each element must have an additive and multiplicative inverse — meaning every number a has a number that you can add to it to get $0$ and a number that you can multiply by it to get to $1$ (but $0$ is special and doesn’t have a multiplicative inverse). So the rational numbers are a field, but the integers are not.

### Set notation

We can think of $S$ as a collection of objects $a, b, \dots$. We will usuall use "braces" when defining a set. E.g.

$$S = \{a, b, \dots \}$$

If we wish to express that a particular element $s$ is contained within a set $S$, then we will write $s \in S$.

Sometimes we will define sets using conditions, there is a special notation for this. For example, we could define the set of rational numbers as:

$$\mathbb{Q} = \{x \in \mathbb{R} ~|~ x=\mathfrac{a}{b} for some a, b \in \mathbb{Z} \}$$
