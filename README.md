# Tailwind CSS text-opacity unexpected behavior

This repository demonstrates an uncommon bug related to the `text-opacity` utility in Tailwind CSS. The issue arises from a misunderstanding of how `text-opacity` functions. It affects the opacity of the text color, but not the background color of the element.

## Bug Description

The provided code snippet uses `text-opacity` expecting to make the entire element semi-transparent, however, it only affects the text.  The background remains fully opaque.

## Solution

To achieve semi-transparency of the entire element, use `bg-opacity` instead of `text-opacity` or combine both as needed for specific effects.

## How to reproduce

1. Clone this repository.
2. Open the `bug.html` file in your browser. You will see that the text is semi-transparent but the background is fully opaque.
3. Open the `bugSolution.html` file. You will see the corrected behavior where both text and background have the expected transparency.
