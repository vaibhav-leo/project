We can use a multiword properties in objects but they must be quoted.
```jsx
let user = {
  name: "vaibhav",
  age: 26,
  "likes anime": false
};
```
- to access these properties we cannot use dot notation like - ``user.likes anime``
- instead we need to use square brackets - ``user["likes anime"]``
