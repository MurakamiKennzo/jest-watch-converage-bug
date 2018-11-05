## follow the step

* Run `npx jest --watch` (should show unknown coverage)
* add test in ____tests____/index.test.js like this:

```js
// ...
it('works with `import`', () => {
  expect(double(6)).toBe(12);
});
```

 (should show unknown coverage)

* press key P, enter 'index'(should show correct)
