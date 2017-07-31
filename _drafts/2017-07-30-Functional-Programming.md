---
layout: post
title:  "Functional Programming"
categories: functional
---
# Functional programming

## History

### Why it matters

- Readability
- Testability
- Re-use
- Performance
  - Parallelism
  - Caching

## Theory

### Pure Functions

A pure function is a function which:

- Given the same input, will always return the same output.
- Produces no side effects.
- Relies on no external mutable state.

#### Pure Function Examples

{% highlight javascript %}
function foo() {
    return 1;
}
function bar(x) {
    return x * 3;
}
function baz(x, y) {
    return (2*x) + (3*y);
}
{% endhighlight %}

### Higher Order Functions



### Currying

## Practice

### First Class Functions

### Javascript

#### How JS and FP are made for each other

#### Unidirectional Data Flows

##### React

##### ELM

## Conclusion

