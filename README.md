# Incorrect innerHTML Appending in HTML

This repository demonstrates an uncommon bug related to the usage of `innerHTML` in HTML. The bug arises from appending new content to the existing content of an element using `innerHTML`.  In many cases this will overwrite the content instead of appending.  This example shows how to correctly append content using innerHTML and DOM manipulation for clarity.

## Bug Description

The `bug.html` file contains an example where `innerHTML` is used to append text to a div element. However, the original content of the div is replaced, leading to unexpected behavior. The intention is to add new text at the end, but the result is just the new text displayed.

## Solution

The solution presented in `bugSolution.html` demonstrates the correct way to append text to a div element using `innerHTML`. 