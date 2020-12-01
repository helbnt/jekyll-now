---
categories: geek
---

Now that it appears the website issues are back under control, I can move on
with more Javascript practice. Before the snafu with updating the Grav theme I
was using, I was working on some pretty basic stuff in Javascript, mainly
reversing a string. In the post about it, I detailed using Javascript's built-in
functions to accomplish the task. I mentioned that there was a way to also do
the same thing using Loops, and that was what I was going to practice with next.
<!--more-->
While looking over some of the examples to try and understand things better, I
found that in latest version of Javascript -- ES6 -- there's now a `for...of`
statement that loops over "iterable objects". Quite frankly, I wasn't sure what
"iterable" meant (I figured it had to do with counting objects), so I looked
that up. Boy, I wish I hadn't.

I did a simple right-click -> lookup on the word "iterable" to see what Apple
says the definition is. Their definition came from Wikipedia which says:

> In mathematics, an iterable cardinal is a type of large cardinal introduced by
> Gitman, and Sharpe and Welch, and further studiedby Gitman and Welch. Sharpe and
> Welch defined a cardinal κ to be iterable if every subset of κ is contained in a
> weak κ-model M for which there exists an M-ultrafilter on κ which allows for
> wellfounded iterations by ultrapowers of arbitrary length.

ಠ_ಠ

I'm not a mathematician, and now I know why. That's a bunch of gobbly-gook right
there.

But onto trying to figure out what the `for...of` loop accomplishes and how it
works.

At first, the syntax seems fairly straight forward: for (variable of iterable) {
statement} But once I combined that with the reverse string example:

```javascript
function reverse(str) {
  let reversed = "";
  for (let char of str) {
    reversed = char + reversed;
  }
  return reversed;
}
```

I started getting confused. At first glance upon looking at the syntax, it seems simple enough: for a variable of the iterable, do something. But looking at the reverse string example, it first sets reversed to an empty string, and in the for...of loop, it does a let char of
str. OK, so, let the character of the str parameter we pass as an argument to
the reverse function be reversed by adding the char to the reversed variable.

And then return that variable.

I am so confused. I try talking (or, in this case, writing) the logic out-loud
in hopes that it'll stick to some part of my brain, but this time, not so much.
How is it deciding the reverse the string? This is a big part of why Javascript
(and really, programming in general) doesn't make sense to me. There seems to be
something going on that a lot of more practiced developers take for granted that
I'm just not getting.

I'll keep plugging away and report back later if I have anything of value or
makes sense.

Meanwhile maybe I should write about butterflies or something. They're pretty.
