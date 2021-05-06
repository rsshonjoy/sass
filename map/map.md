## Maps

```scss
$font-weights: (
  'regular': 400,
  'medium': 500,
  'bold': 700,
);
```

### use scss Maps

```scss
body {
  font-weight: map-get($font-weights, bold);
}
```
