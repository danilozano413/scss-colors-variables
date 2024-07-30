# Scss Colors Variables

## Installation

### Install by NPM

```bash
    npm i scss-colors-variables --save
```

## Usage

Add precompiled scss to your global style scss file

```scss
@import 'scss-colors-variables';
```

or

Add compiled css

```scss
@import 'scss-colors-variables/css';
```

### Set your colors

For adding your own color theme, create a variables style file importing the plugin variables:
```scss
@import 'scss-colors-variables/variables';
```
And redeclare the modified variables following [plugin conf](src/variables/index.scss). As example for modify the colors for ligh and dark theme:
```scss
@import "scss-colors-variables/variables";

$colors_light: (
  primary: #5260ff,
  secondary: #3dc2ff,
  tertiary: #570510,
  success: #2dd36f,
  warning: #ffc409,
  danger: #eb445a,
  dark: #222428,
  medium: #92949c,
  light: #f4f5f8,
);

$light: (
  colors: $colors_light,
  config: $colors_config_light,
  opposed: $colors_opposed_light,
);

$colors_dark: (
  primary: #6a64ff,
  secondary: #50c8ff,
  tertiary: #045023,
  success: #045023,
  warning: #a08106,
  danger: #570510,
  dark: #f4f5f8,
  medium: #989aa2,
  light: #222428,
);

$dark: (
  colors: $colors_dark,
  config: $colors_config_dark,
  opposed: $colors_opposed_dark,
);

$colors_scheme: (
  light: $light,
  dark: $dark,
  contrast: $contrast,
);

```


## TODO

- Add package for regenerate variables with loaded colors from external source
- Add contribution docs

## Use with ionic

Read my other library to compile for Ionic with some helpers [Ionic Scss Utils](https://github.com/danilozano413/ionic-scss-utils)

## Libraries compatibility

- [Tailwindcss](https://tailwindcss.com/) ([See tailwind config doc](./TAILWIND_CONFIG_DOC.md))
- [Angular Material](https://material.angular.io/) ([See material config doc](./MATERIAL_CONFIG_DOC.md))
- [Ionic Framework](https://ionicframework.com/)
- [Ionic Scss Utils](https://github.com/danilozano413/ionic-scss-utils)
