
```js
function validate(val, errorMsg = "default error") {
  if (/*the value is bad*/) {
    throw new Error(errorMsg);
  }

  return val;
}
```
