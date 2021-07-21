---
layout: post
title: "What is this thing called Painlev&eacute;?"
subtitle: The beginning of the journey
date: 2021-07-13
---

Imagine you want to define &ldquo;new&rdquo; functions, where <i>new</i> means functions that cannot be expressed in terms of functions you already know. Imagine that equations they satisfy arise in a wide range of applications. 

This is the starting point of the journey that led to differential equations called the <i>Painlev&eacute; equations</i> and difference equations called the <i>disrcrete Painlev&eacute; equations</i>. The aim of this post is to describe this mathematical journey. Here are a few of these equations:
\(
&{\rm d}\textrm{P}_{\textrm{I}}:\ w\,(\overline w+w+\underline w)=a\,n+b+c\,w,\\
&{\rm q}\textrm{P}_{\textrm{I}}:\quad  \overline w\,\underline w =\frac{1}{w}-\,\frac{1}{a\;q^n\, w^2},\\
&{\rm e}\textrm{RCG}:\ \\
&{\rm cn}(\gamma_n){\rm dn}(\gamma_n)\big(1-k^2{\rm sn}^4(z_n)\big)w_n\big(w_{n+1}+w_{n-1}\big)\\
 &-{\rm cn}(z_n){\rm dn}(z_n)\big(1-k^2{\rm sn}^2(z_n){\rm sn}^2(\gamma_n)\big)\cdot\\
 &\phantom{-{\rm cn}(z_n){\rm dn}(z_n)\big(1}\cdot\big(w_{n+1}w_{n-1}+{w_n}^2\big)\\
&+\big({\rm cn}^2(z_n)-{\rm cn}^2(\gamma_n)\big){\rm cn}(z_n){\rm dn}(z_n)\cdot\\
&\phantom{-{\rm cn}(z_n){\rm dn}(z_n)\big(1}\cdot\big(1+k^2{w_n}^2w_{n+1}w_{n-1}\big)\,=0,
\)

where
\(
   z_n=(\gamma_e+\gamma_o)n+\omega , \,\,\,\,\,
         \gamma_n=\begin{cases}\gamma_e ,\ \textrm{for}\ n=2j,\\
           \gamma_o ,\ \textrm{for}\ n=2j+1,
           \end{cases}
         \)
  with \(\gamma_e\), \(\gamma_o\), \(a\), \(b\), \(c\), \(d\), \(q\) being constants, with \(q\not=0,
  1\) and where cn, dn, sn denote <a href="https://dlmf.nist.gov/22">Jacobi elliptic functions</a>. 

This journey turns out to be so broad and the details so rich that I will have to expand the steps in different staging posts. The impatient reader may want to jump in with both feet by watching the <a href="https://ww3.math.ucla.edu/news-events/distinguished-lecture-series/">videos of lectures</a> I gave at UCLA or reading the introductory article I wrote for Notices of the <a href="ams.org">AMS</a>, whose <a href="http://www.ams.org/journals/notices/202006/rnoti-p797.pdf">PDF</a>  is available.

For those patient enough to go on the journey with me. I invite you to the next post. 

- powered by [Jekyll](http://jekyllrb.com) 
