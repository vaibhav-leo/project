- We can use a multiword properties in objects but they must be quoted.
```jsx
let user = {
  name: "vaibhav",
  age: 26,
  "likes anime": false
};

```
- To access these properties we cannot use dot notation like - ``user.likes anime``.
- Instead we need to use square brackets - ``user["likes anime"]``.

- One interesting usecase of this is when we try to access the ``key`` on runtime.
```jsx
let user2 = {
  name: "Shubham",
  age: 24
};

let key = prompt("What do you want to know about the user?", "name");

// access by variable
alert(user2[key]);

// now, if you try to enter "age" or "name" it will give respective output

```
