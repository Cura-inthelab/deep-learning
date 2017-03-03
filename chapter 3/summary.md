# Chapter 3 Summary of Deep Learning from Scratch

## About Artificial Nueral Programming
Let's see the "previous of NN(Nueorn Network)"
Given b = W_1*x_1 + W_2*x2
"""if b > T then f(a)=1, else if b <= T tehn f(b)=0"""
Where T is threshould value, b is , a is argument,  f(a) is output, W_n is weight for each nueron, x_n is input.

By finding proper W_1, W_2, W_3... we can get "trained nuerons", so what we should do is finding weight for each input.

i.e.) There is four nueron, and output results 1 when two input is 1, else it is 0. what weight values should be?

+ I said book mentioned that only one NN cannot find the answers of XOR.

In this chapter, it begins with redefine formula introduced before.
By replacing """b > T""" with "b - T > 0" parts, it can pass it's value to next nueron. The result of first step of nueron is being the input of next nueron. 

Did you get it? 

The reculsive tactics from algorithm was first thing come up in my head, It is not exactly same though.

## further works
Write a python code snippet that find several variation of OR gate.

## Reference
###Books
- Deep learning from scratch, by Saito Goki, published in 2017-01-03 (translated in Korean)