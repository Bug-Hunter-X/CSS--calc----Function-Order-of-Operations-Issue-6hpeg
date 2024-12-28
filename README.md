# CSS `calc()` Function Order of Operations Issue

This repository demonstrates a subtle bug related to the order of operations within CSS's `calc()` function. When combining percentages and fixed units (like pixels), the browser's interpretation can lead to unexpected results.

## Bug Description

The `calc()` function, while powerful, can be tricky when mixing percentage and absolute units. The order in which calculations are performed isn't always intuitive, sometimes leading to layout discrepancies across browsers or unexpected values.

## Solution

The solution involves carefully restructuring the `calc()` expression. Sometimes using intermediate variables or avoiding mixed units altogether might be necessary. The provided solution shows a way to resolve this issue.