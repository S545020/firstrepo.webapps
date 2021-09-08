# firstrepo.webapps

Welcome to the first repository of web applications

welcome to git bash

---
# Table Creation using Markdown language
Below Table describles the food items that someone must try.This Table consists of food items and the place of items that will be avalible and the cost of the particular food item.
| Name of Food Item | Location | Cost of Item |
| --- | --- | ---: |
| Biryani| Hyderabad | $30 |
| Momos | Kolkata| $10 |
| Pani Puri | Maharashtra | $5 |
| Fish Fry | Kolkata | $25 |
---
# Block Quotes usage in Markdown language
> Life is from the inside out. When you shift on the inside life shifts on the outside. *Marcus Aurelius*

> The Happiness of your life depends on the quality of your thougths. *Seneca*
---
# Code Fencing usage in Markdown language
> The Fibonacci Sequence is the series of numbers(0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...). The next number is found by adding up the two numbers before it. For Example: the 2 is found by adding the two numbers before it (1+1), the 3 is found by adding the two numbers before it (1+2),the 5 is (2+3), and so on!

Link to Fibaonacci Source  <https://www.mathsisfun.com/numbers/fibonacci-sequence.html>
```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
} 
```
Link to the source code <https://cp-algorithms.com/algebra/fibonacci-numbers.html>
