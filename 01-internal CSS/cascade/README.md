## cascade

The cascade is the conflict resolution system of CSS
when many rules are applying styles to the same element the cascade chooses which one wins
the cascade resolves with the criteria of 3 rules that decide the final result: !important, id> Class> Tag, the last rule wins

### !important

it is a special level of priority that is activated with !important, this allows forcing a rule that contains !important over other rules. the disadvantage is that if !important is abused it can break the CSS structure, that is why professionally it is avoided

### specificity

specificity is a numeric weight system where the greater the number the greater the specificity, as a mental model we can say that the approximate weight is:
inline style = 1000
ID = 100
class = 10
tag = 1

### order of appearance

if two rules have exactly the same weight, the change of the last rule that was added will be shown, that is, the last one to be written in the CSS is the one that will override the others with the same weight.

#### also taken into account:

browser (user agent)
user
author (CSS)
