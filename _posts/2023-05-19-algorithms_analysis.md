---
layout: post
title: "Algorithms Analysis"
categories: Algorithm
tag: [test, test2]
author_profile: true
---

# Algorithms Analysis

When you write a program or subprogram you should be concerned about the resource needs of the program. The two main resources to consider are time and memory. The amount of resources consumed often depends on the amount of data you have. It will also take more time for an algorithm to run. In other words what we really care about is the growth rate of resource consumption with respect to the data size.

## Time Resource

Each operation that your program performs requires time. The more operations you do, the more time it will take. Thus, one way that we can measure the amount of time required by an algorithm is to measure how many operations it performs. When doing this, we make the assumption that every operation has the same time cost.

## Memory Resource

This is not calculated by operation count because the number of operations doesn't always increase memory consumption. However, we can still make a calculation on this based on variable declarations, dynamically allocated memory etc.

# Growth Rates

Algorithms analysis is all about understanding growth rates. It is about understanding the growth in resource consumption as the amount of data increases. Typically, we describe the resource consumption growth rate of a piece of code in terms of a function (a "curve").

## Constant

A constant resource need is one where the resource need does not grow. That is processing 1 piece of data takes the same amount of resource as processing 1 million pieces of data.

![Constant resource graph](/images/2023-05-19-algorithms_analysis/constant_resource_graph.jpeg "Constant")







