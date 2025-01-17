# Uncommon HTML Bug: innerHTML Misuse

This repository demonstrates an uncommon bug related to the misuse of `innerHTML` in HTML.  Improper use of `innerHTML` to inject HTML content can lead to unexpected page behavior and potential security vulnerabilities if not handled carefully.

The bug involves directly inserting HTML content into an element using `innerHTML` without proper sanitization or consideration for potential HTML tags within the injected string. This can lead to unintended consequences, particularly when the injected string is derived from user input or external sources.

The solution demonstrates a safer approach using DOM manipulation techniques, ensuring better control and avoiding potential issues.