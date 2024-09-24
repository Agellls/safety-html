# Tutorial to make your html safety

✅ This method its working perfectly except its remove from inspect element too its still cannot copy, paste, or cut. because its read 1 time when page open.
<br>

```js
// its make your text cannot select
onselectstart = "return false";
```

```js
// its make your form cannot paste from users
onpaste = "return false";
```

```js
// its make your text cannot copy
onCopy = "return false";
```

```js
// its make your text cannot cut
onCut = "return false";
```

```js
// its make your site cannot drag
onDrag = "return false";
```

```js
// its make your site cannot drop
onDrop = "return false";
```

## Example to inside a element html

```html
<form action="">
  <input
    type="text"
    name="name"
    id="name"
    onpaste="return false"
    oncut="return false"
    oncopy="return false"
    placeholder="Try paste or copy your text if you can"
    style="width: 600px; padding: 8px;"
  />
</form>
```

Thats all thanks for reading my repository, Happy coding 😁👍
