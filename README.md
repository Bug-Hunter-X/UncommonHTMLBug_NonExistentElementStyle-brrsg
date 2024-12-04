# Uncommon HTML Bug: Accessing Non-Existent Element Style

This repository demonstrates a subtle bug in HTML where attempting to access the style property of a non-existent element can cause unexpected behavior.  The bug occurs when JavaScript code tries to manipulate the style of an element that does not exist in the DOM.

## Bug Description

The bug.html file contains a simple HTML structure with a div element with the id 'myDiv'. The script attempts to access a non-existent element ('nonExistentElement') and modify its style. This throws an error which may prevent subsequent script execution if not handled properly.

## Solution

The solution.html file provides a fix where the script first checks if the element exists before attempting to change its style.  This prevents the error and ensures the rest of the script functions correctly.
