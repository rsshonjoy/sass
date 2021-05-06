## Indented Syntax

```
@mixin button-base()
  @include typography(button)

  display: inline-flex;
  position: relative;
  height: $button-height;
  border: none;
  vertical-align: middle;

  &:hover
    color: #34495e;
    cursor: pointer;
```
