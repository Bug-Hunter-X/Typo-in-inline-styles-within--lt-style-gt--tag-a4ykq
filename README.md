# Uncommon HTML Bug: Typo in Inline Styles

This repository demonstrates a subtle bug that can occur in HTML when using inline styles within the &lt;style&gt; tag.  A simple typo in a CSS property can lead to unexpected visual results, making it difficult to debug.

## Bug Description

A typographical error in a CSS property within an inline style definition inside the &lt;style&gt; tag can cause the browser to either ignore the entire style rule or only apply part of it.  The inconsistent behavior makes it harder to track the root cause.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the text does not have the expected styling due to the typo in the `background-color` property.

## Solution

The solution is simple: Correct the typo in the CSS property. The corrected code can be found in `bugSolution.html`.