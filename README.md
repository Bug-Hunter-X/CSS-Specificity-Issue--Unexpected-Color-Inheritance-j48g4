# CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS specificity and inheritance in nested elements.  The problem arises from unexpected behavior when combining selectors with varying specificity, leading to colors not rendering as intended.

## Bug Description
The CSS code contains rules targeting nested `<p>` elements within `<div>` elements. Despite the apparent specificity of the selectors, the rendered color may not match the expectations based on the presumed cascade.

## Solution
The solution involves careful review of CSS specificity rules and adjusting selectors to ensure desired precedence.  This might involve using more specific selectors, !important (use sparingly!), or reorganizing the CSS to correctly reflect the desired inheritance and overrides.