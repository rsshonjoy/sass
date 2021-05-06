<p align="center">
  <h1 align="center">SCSS for Bigenners</h1>
  <h3 align="center">--- SASS Maps ---</h3>

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
