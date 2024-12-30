# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates a subtle bug related to using `innerHTML` in HTML. The bug occurs when you add new elements of the same type within an existing element using `innerHTML`.

## Bug Description
The issue arises when attempting to insert a `<p>` element inside a `<div>` element using `innerHTML`. The unexpected outcome can sometimes be the loss of functionality for the parent element.  This demonstrates an edge case that might not be immediately apparent to developers.

## Reproduction Steps
1. Open `bug.html` in a web browser.
2. Observe the behavior of the paragraph elements within the div.