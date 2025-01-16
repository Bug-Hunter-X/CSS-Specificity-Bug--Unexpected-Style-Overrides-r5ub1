# CSS Specificity Bug

This repository demonstrates a common issue in CSS: specificity problems leading to unexpected style overrides.  The `bug.css` file contains the buggy CSS code, while `bugSolution.css` offers a corrected version.

The problem arises because a more specific selector unintentionally overrides a more general one, causing styles to be applied incorrectly.  The solution involves understanding and adjusting CSS specificity to ensure styles are applied as intended.

## Setup

1. Clone this repository.
2. Open `index.html` in your web browser to view the results.

## Solution

The solution involves carefully analyzing the CSS selectors and adjusting their specificity to ensure the desired styles take precedence.  This often means making the general selectors more specific or refactoring the CSS to avoid the conflict altogether.