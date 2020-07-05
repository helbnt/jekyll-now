---
categories: geek
title: Practice&#58; JS
---

I'm between projects at work, and there's only so much reddit I can peruse. One
of the skills essential for a front end developer nowadays is Javascript and my
skills have always been rusty at best. Rather than play on social media or my
phone, I'm going to work on becoming more comfortable with Javascript. It's
certainly a better use of my time.

There are dozens and dozens of resources out there, both free and paid. I think
I'll start with some basics on YouTube and work my way over to [freecodecamp](https://freecodecamp.org). Or maybe vice-versa. Who knows. I'm also going to show what I'm learning here, and present it as if I were teaching you to code. I think that will help my overall
learning process.

I'm going to start by trying to solve a question I was asked in an interview
some months back, and see if I can work through that: Reverse a string. Let's
go!

One of the best sources on finding how to do, well, anything in this world is
Google. Doing a search for "Reverse a string in Javascript" returns over 22
million hits. I definitely should be able to find something to answer this
question then!

The first site returned talks about using Javascript's built-in functions.
Namely, `split()`, `reverse()`, and `join()`. If you read those functions by
themselves, they make sense: Split, we're going to split the string, then we'll
Reverse their order, and then we'll Join them back together.

The actual function looks like this

```javascript
function reverseString(string) {
  return string.split("").reverse().join("");
}
reverseString("I can learn this!");
```

Utilizing Chrome's Developer Tools, I used the console, copied that in, and
"!siht nrael nac I" was returned. Here's a breakdown of what's happening:

First, we use `split()` to take the string "I can learn this!" and turn it into an
array: i.e., `["I", " ", "c","a","n"," ","l","e",...]` Notice that the spaces are
included in that split.
Next, `reverse()` takes that new array created by `split()` and reverses it. `["!", "s", "i", "h", "t", " ", "n", "r", "a", "e", "l", ...]`
Finally, `join()` is used to join the letters in the new array back together.

Fairly simple once you break it down. Really, my biggest issue with this
apparent mental block about learning Javascript (aside from the fact that I just
don't seem to use it enough in everyday work), is the syntax. Parenthesis () vs.
Curly braces {}. When to use them, and when to add a closing semi-colon. This
really just comes down to practice for me, and hopefully doing something like
this blog post on a daily, even weekly basis, will help with that.

There are other ways to reverse strings. That's something that's true a great
deal of the time in programming (and in life really); there's always another way
to do something. One of those ways is using a For Loop. Because loops are an
important part of programming in general, I'm going to tackle that in my next
post.
