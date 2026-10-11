# Ranking Algorithm — Tachyon House Points

## Overview

The application ranks four houses — ALPHA, INFER, MATRIX, and LAYER — based on their total points.

## How It Works

1. Collect the current points of all four houses.
2. Sort the houses in descending order of points.
3. Assign ranks based on their positions.
4. Houses with equal points share the same rank.
5. Display the house or houses with the highest positive score as the winner.

## Example

| House | Points | Rank |
|---|---:|---:|
| INFER | 120 | 1 |
| LAYER | 100 | 2 |
| MATRIX | 80 | 3 |
| ALPHA | 50 | 4 |

## Tie Example

When two houses have equal points, they share the same rank. The next rank skips the tied position.

| House | Points | Rank |
|---|---:|---:|
| INFER | 120 | 1 |
| ALPHA | 100 | 2 |
| LAYER | 100 | 2 |
| MATRIX | 50 | 4 |

In this example, ALPHA and LAYER are tied for second place with 100 points each. Therefore, both receive rank 2, and MATRIX receives rank 4.
