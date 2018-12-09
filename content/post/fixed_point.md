---
layout: post
title:  "A small point about Fixed Point..."
date:   2015-09-17 12:21:21
categories: programming
draft: false

---

### Fixed-point ?

The [fixed-point of a function][link_fixed_point_definition] \\(f(x)\\) is a value \\(x\\) such that the equation \\(f(x) = x\\) is true. 

For example, \\(0\\) is a fixed-point of the familiar trigonometric function \\(sin\\), since \\(sin(0)=0\\). 

Starting with this simple definition, I was shown some amazing piece of programming by [Prof. Gerald Jay Sussman][link_prof_Sussman] in the legendary [SICP][link_SICP] course (`lecture-2A` to be specific). 

Inspired by the lecture, I quickly scribbled the following piece of code _verbatim_ in my [Scheme][link_scheme] environment. 

And **lo & behold!**

The program I wrote JUST WORKED the first time itself! 

Truly a testament to great teaching, and also to a great programming language (LISP that is--Scheme being a clean lit'l dialect of it :-) ). 

Hat-tip to both! :hearts: :blush:

### Over to the code...

---

{{< gist raghuugare a5a70ee8757a11c0ebb864a73365f129 >}}

---

And then I tested it with the following calls to my `fixed-point` function:

---

{{< gist raghuugare 92d75b517a8465410e27871102d6b284 >}}

---

### The point?

Well, in the end, especially on seeing the different values in case of the \\( sin() \\) function, I realized one simple thing---even the so-called 'fixed-point' of a function 'changes'.

Which reminds me of the saying:

>  &#10077; The ONLY constant in Life, is CHANGE! &#10078; :blush:

**Happy Learning & Exploring with SICP ! :~)**

[link_scheme]: https://en.wikipedia.org/wiki/Scheme_(programming_language)
[link_fixed_point_definition]: https://en.wikipedia.org/wiki/Fixed_point_(mathematics)
[link_prof_Sussman]: https://en.wikipedia.org/wiki/Gerald_Jay_Sussman
[link_SICP]: https://mitpress.mit.edu/sicp/
