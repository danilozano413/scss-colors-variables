# Material theming Config

For integrate with material colors theming, you can assign the generated variables to theme
on your styles file:

```scss
@use "@angular/material" as mat;

@include mat.core();

$primary: (
  default: var(--color-primary),
  lighter: var(--color-primary-light),
  darker: var(--color-primary-dark),
  text: var(--color-primary),
  default-contrast: var(--color-primary-contrast),
  lighter-contrast: var(--color-primary-light-contrast),
  darker-contrast: var(--color-primary-dark-contrast)
);
$accent: (
  default: var(--color-secondary),
  lighter: var(--color-secondary-light),
  darker: var(--color-secondary-dark),
  text: var(--color-secondary),
  default-contrast: var(--color-secondary-contrast),
  lighter-contrast: var(--color-secondary-light-contrast),
  darker-contrast: var(--color-secondary-dark-contrast)
);

// Define a light theme
$light-theme: mat.define-light-theme(
  (
    color: (
      primary: $primary,
      accent: $accent
    )
  )
);

@include mat.core-color($light-theme);

```
