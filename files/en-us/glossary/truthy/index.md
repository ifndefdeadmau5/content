---
title: Truthy
slug: Glossary/Truthy
tags:
  - CodingScripting
  - Glossary
  - JavaScript
---
In {{Glossary("JavaScript")}}, a **truthy** value is a value that is considered `true` when encountered in a {{Glossary("Boolean")}} context. All values are truthy unless they are defined as {{Glossary("Falsy", "falsy")}} (i.e., except for `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`, and `NaN`).

{{Glossary("JavaScript")}} uses type {{Glossary("Type_Conversion", "coercion")}} in Boolean contexts.

Examples of _truthy_ values in JavaScript (which will be coerced to true in boolean contexts, and thus execute the `if` block):

```js
if (true)
if ({})
if ([])
if (42)
if ("0")
if ("false")
if (new Date())
if (-42)
if (12n)
if (3.14)
if (-3.14)
if (Infinity)
if (-Infinity)
```

## See also

- {{Glossary("Falsy")}}
- {{Glossary("Type_Conversion", "Coercion")}}
- {{Glossary("Boolean")}}
