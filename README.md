# femto-css

Tiny classless css (Only 1KB gziped.)

[Demo](https://levy42.github.io/femto-css/)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/levy42/femto-css@refs/heads/main/femto.min.css">
```
## Demo (img)
<img width="972" alt="image" src="https://github.com/user-attachments/assets/a1f05175-32ba-428c-8096-11a2c888112b" />

> It is just about simple basic styles.
> No old browser support, no 100% consistency between browsers.
> Framework only targets useers who use modern browsers and update them at least once a year.

## Colors:
`--red`, `--green`, `--blue`

To create a button with custom color, just specify `color` attribute, femto-css uses relative colors to create shades for background, `hover` and `active` states.

## Select
Femto css is using `base-select` appereance, as of April 2025 only Chrome and Edge support it, but it's comming.

## Grid
Use `role="row"` for rows and `aria-colspan=[1-12]` for columns.
