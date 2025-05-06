---
title: "Calculus class reflection day 4"
date: 2025-05-04
categories: [classJournaling, calculus]
tags: [calculus, maths]
image: media/calculusDay4/chainRule.png
---

## The Chains rule
The chains rule in short, is the process for us to find derivates out of composite function. Composite function themselves are function made out of multiple smaller functions inside. To give an example let's say there's this formula as follows:
 >_f(x) = (x^2)+2x+1_

 Which in return, the derivative is:
 >_f'(x) = 2x + 2_

 Pretty straightforward, but what if we come across a function that look like this: _f(x) = (x + 1)^100_ ? If we try to find the derivative of it in a traditional way, it would be a tedious and time-consuming work. As such, we use chains rule to solve this.
 The formula is simple. We take the composite formula and break it down like this:
 >_f(x) = g^100_ Where the g is _x + 1_

Then we find the derivative for each part of the function we just broke down.
> _df(x)/dg * dg/dx_
>> _100g^99 * 1_ = _100((x + 1)^99)_

Thus, we get the derivate result from that chains rule implemention.
