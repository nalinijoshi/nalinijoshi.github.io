---
layout: post
title: "What is this thing called Painlev&eacute;?"
date: 2021-07-13
---

Imagine you want to define &ldquo;new&rdquo; functions, where <i>new</i> means functions that cannot be expressed in terms of functions you already know, those that are classical elementary functions. 
Imagine that they satisfy some equations that arise in a wide range of applications. Where would you start? 

This post is the beginning of a description of this surprising rich field, which turns out to lie at 
the intersection of many directions in mathematics, including  dynamical systems theory, differential or difference Galois theory and algebraic geometry. 
Readers who want to dive straight in might want to check out the <a href="https://www.math.ucla.edu/dls/nalini-joshi">videos of lectures</a> I gave at UCLA.
Another starting point is an article I wrote for Notices of the <a href="ams.org">AMS</a>: check out the <a href="http://www.ams.org/journals/notices/202006/rnoti-p797.pdf">PDF</a> of the article.

To understand a little more, you need to know the mathematical term "transcendental". Start with the counting numbers
\$$ 1, 2, 3, \ldots $$.
Addition and subtraction of counting numbers lead to the integers
\$$ 1+3=4, 5-8=-3, \ldots $$.
Multiplication and division lead to rational numbers
\$$ 1/2, 0.3333\ldots $$.
<table rules="groups">
  <thead>
    <tr>
      <th style="text-align: left">Integers</th>
      <th style="text-align: center">Algebraic numbers</th>
      <th style="text-align: right">Transcendental numbers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">\$$ 2, -11$$ </td>
      <td style="text-align: center">\$$ \sqrt{2}, 2/3^{1/5}$$ </td>
      <td style="text-align: right">\$$ e, \pi$</td>
    </tr>
  </tbody>
</table>
Solving polynomial equations with integer coefficients leads to algebraic numbers. But there are numbers called "transcendental numbers" that escape algebraic construction. 
These lie in places on the number line that are like regions in old maps filled with drawings of fabulous monsters. Although the name imbues them with a mystical aura, 
they arise everywhere in real life, as we know from the presence of the number &pi; in almost every part of mathematics. This post is about functions that play a similar role.

To get to such functions, imagine replacing counting numbers with polynomials.  Multiplication and division of polynomials lead to rational functions. 
Solving polynomials of more than one variable leads to algebraic functions. Functions that are not algebraic are called <i>transcendental functions</i>.

 Within this class, there is a ladder of transcendentality. At the base level are familiar transcendental functions, such as exponential, 
 trigonometric and logarithmic functions. But there are higher level functions that escape any algebraic operations applied to these or their compositions.

 The exploration of transcendental functions has a long history, reaching back at least to Euler in 1755. One enduring question is whether a newly 
 discovered function can be expressed in terms of earlier known transcendental functions. As for transcendental numbers, the main question here is to ask 
 whether there exist algebraic relations between them. Derivatives or differences of transcendental functions also play a crucial role in answering such questions. 

 Each new level of transcendentality aims to capture functions that escape the previous steps. There is a hierarchy of known cases, which arise as 
 solutions of differential or difference equations. Functions in the hierarchy are categorized according to whether or not they result from operations called 
 <i>classical operations</i> applied to functions at a previous step.
 
 So what are currently known transcendental functions that are furthest away from polynomials, at the top of the known hierarchy of functions solving polynomial differential 
 or difference equations? They are solutions of equations
 called the <i>discrete Painlev&eacute; equations</i> or <i>Painlev&eacute; equations</i>.

- powered by [Jekyll](http://jekyllrb.com) 
