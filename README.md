Highlight leading tabs:

```javascript
patterns = (
  { name = 'source.illegal.invalid.leading-tab';
    match = '^( *\t+)';
    captures = { 1 = { name = 'invalid.illegal.leading-tab'; }; };
  },
  ...
```