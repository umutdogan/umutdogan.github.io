---
title: Algorithms
layout: post
date: '2018-10-31 01:00:23 +0300'
categories:
- algorithms
tags:
- algorithms
---

In mathematics and computer science, an algorithm is an unambiguous specification of how to solve a class of problems. Algorithms can perform calculation, data processing and automated reasoning tasks.

As an effective method, an algorithm can be expressed within a finite amount of space and time and in a well-defined formal language for calculating a function. Starting from an initial state and initial input (perhaps empty), the instructions describe a computation that, when executed, proceeds through a finite number of well-defined successive states, eventually producing "output" and terminating at a final ending state. The transition from one state to the next is not necessarily deterministic; some algorithms, known as randomized algorithms, incorporate random input.

The concept of algorithm has existed for centuries. Greek mathematicians used algorithms in, for example, the sieve of Eratosthenes for finding prime numbers and the Euclidean algorithm for finding the greatest common divisor of two numbers.

The word algorithm itself derives from the 9th Century mathematician Muḥammad ibn Mūsā al-Khwārizmī. A partial formalization of what would become the modern concept of algorithm began with attempts to solve the Entscheidungsproblem (decision problem) posed by David Hilbert in 1928. Later formalizations were framed as attempts to define "effective calculability" or "effective method". Those formalizations included the Gödel–Herbrand–Kleene recursive functions of 1930, 1934 and 1935, Alonzo Church's lambda calculus of 1936, Emil Post's Formulation 1 of 1936, and Alan Turing's Turing machines of 1936–37 and 1939.

<p align="center">
    <a href="https://xkcd.com/26/" target="_blank"><img src="../../images/2018-10-31-algorithms.jpg" alt="Fourier" title="Fourier" /></a>
</p>

## Design
Algorithm design refers to a method or mathematical process for problem solving and engineering algorithms. The design of algorithms is part of many solution theories of operation research, such as dynamic programming and divide-and-conquer. Techniques for designing and implementing algorithm designs are also called algorithm design patterns, such as the template method pattern and decorator pattern.

One of the most important aspects of algorithm design is creating an algorithm that has an efficient run-time, also known as its Big O.

Typical steps in development of algorithms:
1. Problem definition
2. Development of a model
3. Specification of algorithm
4. Designing an algorithm
5. Checking the correctness of algorithm
6. Analysis of algorithm
7. Implementation of algorithm
8. Program testing
9. Documentation preparation

## Example
One of the simplest algorithms is to find the largest number in a list of numbers of random order. Finding the solution requires looking at every number in the list. From this follows a simple algorithm, which can be stated in a high-level description English prose, as:

High-level description:
1. If there are no numbers in the set then there is no highest number.
2. Assume the first number in the set is the largest number in the set.
3. For each remaining number in the set: if this number is larger than the current largest number, consider this number to be the largest number in the set.
4. When there are no numbers left in the set to iterate over, consider the current largest number to be the largest number of the set.

## Algorithmic Analysis
It is frequently important to know how much of a particular resource (such as time or storage) is theoretically required for a given algorithm. Methods have been developed for the analysis of algorithms to obtain such quantitative answers (estimates).

## Classification
There are various ways to classify algorithms:

### By implementation
1. Recursion
2. Logical
3. Serial, parallel or distributed
4. Deterministic or non-deterministic
5. Exact or approximate
6. Quantum algorithm

### By design paradigm
1. Brute-force or exhaustive search
2. Divide and conquer
3. Search and enumeration
4. Randomized algorithm
5. Reduction of complexity
6. Back tracking

### Optimization problems
1. Linear programming
2. Dynamic programming
3. The greedy method
4. The heuristic method

### By field of study
Every field of science has its own problems and needs efficient algorithms. Related problems in one field are often studied together. Some example classes are search algorithms, sorting algorithms, merge algorithms, numerical algorithms, graph algorithms, string algorithms, computational geometric algorithms, combinatorial algorithms, medical algorithms, machine learning, cryptography, data compression algorithms and parsing techniques.

### By complexity
Algorithms can be classified by the amount of time they need to complete compared to their input size:
1. Constant time
2. Linear time
3. Logarithmic time
4. Polynomial time
5. Exponential time

###### References:
1. [https://en.wikipedia.org/wiki/Algorithm](https://en.wikipedia.org/wiki/Algorithm)
2. [https://www.geeksforgeeks.org/fundamentals-of-algorithms](https://www.geeksforgeeks.org/fundamentals-of-algorithms)

###### Books:
* [Introduction to Algorithms, 3rd Edition (The MIT Press)](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844)
* [Algorithms (4th Edition)](https://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X)
* [Data Structures and Algorithms in Java, 6th Edition](https://www.amazon.com/Data-Structures-Algorithms-Java-6th-ebook/dp/B00JDRQF8C)