# Groovy NullPointerException in List Iteration

This example demonstrates a common NullPointerException in Groovy when a method expects a List but receives a null value.
The `myMethod` function attempts to iterate over the input list, and if `list` is null, this causes a NullPointerException.

## Bug
The bug lies in the `myMethod` function. It doesn't handle the case where `list` might be null.

## Solution
The solution involves adding a null check before iterating the list.