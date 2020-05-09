# Abstract Algebra

## Sets

One of the most fundamental things in mathematics is a **set**. You can think of a set like a box that contains things. We call the things inside a set the **elements** of a set, and say that the set **contains** those elements. We write a set by using these curly brackets: $\{\cdots\}$. What sorts of things can we put in sets? Anything, really. Here is an example set that contains $\text{cat}$, $\text{dog}$, and $\text{mouse}$:

$$\left\{\text{cat}, \text{dog}, \text{mouse}\right\}$$

Like a box, there is no order to things in a set. Here are two more ways to write the same set:

$$\begin{array}{cc}
   \left\{\text{mouse}, \text{cat}, \text{dog}\right\} & \left\{\text{dog}, \text{mouse}, \text{cat}\right\}
\end{array}$$

All of these represent the same box: they contain the same three things. The only thing that matters is if an object is in the set or if it is not. This is a different set:

$$\left\{\text{cat}, \text{dog}\right\}$$

There is no concept of how many of the same thing are in the box. It does not really make much sense to write $\left\{\text{cat}, \text{cat}, \text{dog}\right\}$, becuase it is the same as $\left\{\text{cat}, \text{dog}\right\}$.

We even can puts sets inside of sets, for example:

$$\left\{\left\{1\right\}, \left\{1, 2\right\}\right\}$$

This is not valid because $1$ appears twice in the set, right? Well, actually, this is fine. Technically, this set does not contain $1$. You can think of this as a box with two other boxes in it, $\left\{1\right\}$ and $\left\{1, 2\right\}$, both of which are different: one contains just the element $1$ and the other contains both the elements $1$ and $2$. We could add $1$ to the set to get a new set:

$$\left\{\left\{1\right\}, \left\{1, 2\right\}, 1\right\}$$

Typically, we only look at sets that contain the same kind of thing, unlike this new set; this one contains both sets and numbers. It is usually easier to talk about things in the set when, if you look at one random element, it is similar to all of the other elements. Earlier we saw two sets of animals; $\left\{\left\{1\right\}, \left\{1, 2\right\}\right\}$ is a set containing sets of numbers.

How many things can we put in a set? As many as we want. In fact, that can be infinite! How do you put an infinite number of things into a box? Well, all of this is just in our heads, right? Here is an example of as set with an infinite number of things, one that you are probably already familiar with:

$$\left\{\cdots, -3, -2, -1, 0, 1, 2, 3, \cdots\right\}$$

The set of whole numbers is so common that it has a fancy symbol that represents it: $\Z$. Fun fact: this comes from "Zahlen", the German word for "numbers".

Sometimes we are given a set by someone describing it to us instead of telling us the exact things that are in it. For example, we could say "the box that contains all of the things in my room". Does this box contain my bed? Yes. Does this box contain my toaster? No, that is in the kitchen. We know what is in the box, but we were not told what the exact things are. Like this, we can say "the set of even numbers larger than 11". We could try writing the set like this:

$$\left\{12, 14, 16, 18, \cdots\right\}$$

but this is not a very good way to describe the set, because it is not clear what happens after 18. For example, how would you try writing the set of even numbers larger than 11 whose 1000s digit is not 8? For small numbers, it would look exactly the same, but we know it is different.

### Set operations

So what can we do with sets? One thing we can do is find the size of a set. For sets, we call the size **cardinality**. One way to do this is to count the number of things in the set. For example, what are the cardinalities of these two sets?

$$\begin{array}{cc}
   \left\{\text{cat}, \text{dog}, \text{mouse}\right\} & \left\{\left\{1\right\}, \left\{1, 2\right\}\right\}
\end{array}$$

The first set has cardinality 3 and the second set has cardinality 2. Like before, we only look at the number of things in the outer most box. What about $\Z$? We can't really count all the things in that set because we would be counting forever. For now, we will say that the cardinality is infinite. (What it means for the cardinality to be infinite is actually more complicated, but we will get to that later.)
