# CSS Selector Bug: Attribute Starts-with

This repository demonstrates a subtle bug related to CSS attribute selectors when used with special characters in the attribute values. The bug is that the selector `[attr^=value]` fails to select the target element if the `value` contains special characters that are not properly escaped.