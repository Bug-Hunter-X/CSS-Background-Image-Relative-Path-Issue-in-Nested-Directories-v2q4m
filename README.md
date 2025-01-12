# CSS Background-Image Relative Path Issue in Nested Directories

This repository demonstrates a common issue encountered when using relative paths for `background-image` in CSS within nested directory structures.  The problem arises because the path may not be interpreted correctly relative to the CSS file location.

The `bug.css` file contains the problematic code. `bugSolution.css` provides a solution.

## Problem

The expected behavior is that the background image loads. However, due to a misunderstanding of how relative paths work in this context, the image fails to render.

## Solution

The solution involves carefully constructing the relative path to ensure it's correctly resolved from the CSS file's location.  The correct path is provided in `bugSolution.css`.