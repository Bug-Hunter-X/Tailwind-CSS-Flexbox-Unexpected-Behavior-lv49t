# Tailwind CSS Flexbox Unexpected Behavior

This repository demonstrates an unexpected behavior encountered when using Tailwind CSS classes with flexbox.  The divs don't distribute space as expected.

## Bug Description

When using Tailwind's flexbox utilities, the divs do not evenly distribute space.  One div may overflow or not take up available space.

## Solution

This issue was solved by adding `flex-grow` to the `div` elements.  This ensures that the divs evenly distribute available space within the flex container.
