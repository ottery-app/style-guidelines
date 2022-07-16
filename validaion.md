the main validation function should be called validate.
all validations should return the value unless there is an issue of falure.

```js
function validate(val, errorMsg = "default error") {
  if (/*the value is bad*/) {
    throw new Error(errorMsg);
  }

  return val;
}
```
