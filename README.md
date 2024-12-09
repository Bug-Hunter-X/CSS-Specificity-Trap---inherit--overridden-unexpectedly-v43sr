# CSS Specificity Gotcha: Unexpected `inherit` Behavior

This repository demonstrates a subtle issue related to CSS specificity and the `inherit` keyword.  The problem occurs when a more specific style declaration overrides an `inherit` declaration, leading to unexpected results.  The example illustrates a scenario where the intended inheritance doesn't take place because of a higher-specificity selector.

## Problem

The `inherit` keyword is used to inherit a property from the parent element.  However, in certain cases involving specificity, the `inherit` declaration might not work as expected, and a more specific style will prevail.

## Solution

The solution involves understanding and managing CSS specificity.  Adjust selectors to achieve the desired inheritance behavior.