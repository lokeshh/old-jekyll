---
layout: post
title: "Categorical Index"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Daru just got a new capability => Categorical Index.

Now one can organize vector and dataframe using index that is categorical.

Daru has got now 4 types of indexes to index data:

- Daru::Index
- Daru::MultiIndex
- Daru::DateTimeIndex
- Daru::CategoricalIndex (new)

`Daru::Index` is for usual index where every value is unique.

`Daru::MultiIndex` is for indexing with more than one level.

`Daru::DateTimeIndex` is to have indexing with dates. Its powerful means to analyze time series data.

The new `Daru::CategoricalIndex` is to have data indexed sparsely populated index with each unique index value as category.

This enable use to categorize data into categories.

Let's see an example.

    hello world
    i = Daru::Index.new [:a, :b, :c]
    i
