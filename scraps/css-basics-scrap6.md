In some cases, a particular element may have multiple rule sets that can apply. Let's take a look at an example. For this example, let's assume that we have an HTML `p` element with an id name of `attribution`.

```css
p {
    font-size: 12px;
    color: black;
}

#attribution {
    font-size: 9px;
}
```

In this example, the attribution `p` element will have adopt the following properties:

- `font-size: 9px;`
- `color: black;`
