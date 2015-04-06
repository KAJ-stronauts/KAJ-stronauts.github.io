---
layout: post
title:  "Meeting #20 Notes"
date:   2015-04-06 18:29:00
author: zackary_corbett
categories: notes
---

Today, Dr. Jukes gave us the task of trying to prove the [cosine rule][] using the [sine rule][]. We got somewhere, but we didn't really get anywhere. Eventually, Dr. Jukes just gave us his clever answer.

## Non-geometric Proof of the Cosine Rule by Dr. Kenneth A Jukes

I wondered whether it was possible to prove the cosine rule, $a^2 = b^2 + c^2 – 2bc\cos{A}$, directly from the sine rule $\frac{a}{sinA} = \frac{b}{sinB} =\frac{c}{sinC}$ It is possible, the proof being more complicated than the geometric proof of the cosine rule in that it uses the table of trig identities.

We have $b = \frac{sinB}{sinA}a$ and $c = \frac{sinC}{sinA}a$. Hence

$$b^2 + c^2 -2bc\cos{A} = \frac{\sin^2{B}}{\sin^2{A}} a^2 + \frac{\sin^2{C}}{\sin^2{A}}a^2 - 2\frac{\sin{B}}{\sin{A}}\frac{\sin{C}}{\sin{A}}a^2\cos{A}$$

$$=\frac{a^2}{\sin^2{A}}(\sin^2{B}+\sin^2{C}-2\sin{B}\sin{C}\cos{A})$$

But $A = 180 - (B+C)$ and so

$$\cos{A} = \cos180\cos(B+C) + \sin180\sin(B+C) = - \cos(B+C)$$

whence

$$\sin^2B+\sin^2C-2\sin{B}\sin{C}\cos{A} = \sin^2B+\sin^2C+2\sin{B}\sin{C}(\cos{B}\cos{C} - \sin{B}\sin{C})$$

$$\ldots$$

$$= (\sin{B}\cos{C} + \sin{C}\cos{B})^2$$

$$= (\sin(B+C))^2={(\sin(180-(B+C)))^2}=\sin^2A$$

$$b^2 + c^2 -2bc\cos{A} =\frac{a^2}{\sin^2A}\sin^2A = a^2$$

$$\text{Q.E.D.}$$


**Note:** No meeting next week, 13 April.

[cosine rule]: https://en.wikipedia.org/wiki/Law_of_cosines
[sine rule]: https://en.wikipedia.org/wiki/Law_of_sines