---
id: no-aria-hidden-body
title: "no-aria-hidden-body"
---

# no-aria-hidden-body

Disallow to use aria-hidden attributes on the `body` element.

## How to use

.eslintrc.js

```js
module.exports = {
  rules: {
    "@html-eslint/no-aria-hidden-body": "error",
  },
};
```

## Rule Details

This rule disallows the use of aria-hidden attributes on the `body` element.

Examples of **incorrect** code for this rule:

```html
<body aria-hidden>
  <body aria-hidden="true"></body>
</body>
```

Examples of **correct** code for this rule:

```html
<body></body>
```

## Further reading

- [MDN - Using the aria-hidden attribute](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-hidden_attribute)
