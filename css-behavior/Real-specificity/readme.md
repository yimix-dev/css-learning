# Real specificity

specificity is the central mechanism of conflict resolution in CSS to decide which rule wins when many target the same element

## what problem does it solve?

when many rules apply changes to the same element, specificity comes into play to decide through different criteria which one will win.

## technical definition

Specificity is the numeric weight assigned to a CSS selector that determines its priority over other selectors that target the same element.

This weight is calculated by counting certain types of selectors.

The browser compares those values and the rule with higher specificity wins.

## default behavior

if 2 rules have exactly the same weight the last rule that was written will be applied

also if a rule is not added to change a default value the browser applies one by default, this is known as (user agent)

what type 
