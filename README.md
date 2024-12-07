# Uncommon HTML Event Listener Bug

This repository demonstrates a subtle bug related to adding event listeners in HTML.  The `bug.html` file showcases an incorrect way to add an event listener, which might lead to unexpected behavior.  The correct approach is shown in `bugSolution.html`.  This example highlights a potential point of confusion for developers new to JavaScript event handling within HTML.

## Bug Description
The incorrect usage of `addEventListener` within the HTML file might not result in an immediate error, but it will prevent the event listener from functioning correctly. This is an uncommon issue that could lead to debugging challenges.

## Solution
The solution uses the more direct and concise method of attaching an event listener using the `onclick` property of the element.