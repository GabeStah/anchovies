---
data:
  boss: ''
difficulty:
  very_easy:
    style: 'color: lightgreen;'
    name: Very Easy
  easy:
    style: 'color: green;'
    name: Easy
  moderate:
    style: 'color: yellow;'
    name: Moderate
  hard:
    style: 'color: red;'
    name: Hard
  very_hard:
    style: 'color: #da0000;'
    name: Very Hard
requirement:
title: ''
type: Group
zone: ''
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

-

## Strategy

1.
