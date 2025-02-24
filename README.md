# CSS Specificity Issue

This repository demonstrates a subtle but important issue related to CSS specificity.  The example highlights how an ID selector can override a class selector even when the latter seems more specific.  The key is understanding that ID selectors have higher specificity than class selectors. 

## Bug

The `bug.css` file contains CSS code that unintentionally shows the effect of specificity. An `id` selector with a `div` overrides a `class` selector with a `div` even though the latter appears to be more specific. The solution is provided in `bugSolution.css`.