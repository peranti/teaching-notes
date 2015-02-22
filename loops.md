For loops
===

*Why*
---


*What*
---

Explaining how each element of an iterator is assigned to a
variable, which is then accessed in the body of the for loop:

>
> Let's say your evil-stepmother wants you to peel a sack of potatoes?
> Well, how do you go about doing that? You can't just peel a sack of
> potates, you have to peel each individual potato. When programming
> similar tasks, we can use for loops:
> 
> ```
> for (potato) in (sack of potatoes) {
>   peel(potato)
> }
> ```
> 
> In the above pseudo-code, we write in the body of the for-loop:
> the idented code between the curly braces, what we want to perform
> on each element: in this case, each potato in the sack. In the 
> definition of the for loop, we tell it that we have a "sack of 
> potatoes" (a set of iterables), and that for each "thing" in the
> sack of potatoes, assing that thing to the "potato" variable, then
> perform the steps that occur in the body of the for loop.
> 

This explanation also scales to nested for loops:

```
for (sack) in (sacks of potatoes) {
  for (potato) in (sack) {
    peel(potato)
  }
}
```



