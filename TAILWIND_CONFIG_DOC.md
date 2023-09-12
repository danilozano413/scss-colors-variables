# Tailwind Config

For grant full compatibility with tailwind, we have a example of colors and variables configuration.

on `tailwind.config.js` or `tailwind.config.json`

```json
{
  content: ["./src/**/*.{html,ts,scss}"],
  theme: {
    [...]
    colors: {
      primary: {
        DEFAULT: "var(--color-primary)",
        shade: "var(--color-primary-shade)",
        tint: "var(--color-primary-tint)",
        light: "var(--color-primary-light)",
        dark: "var(--color-primary-dark)",
        opacity: "var(--color-primary-opacity)",
        trans: "var(--color-primary-trans)",
        lucid: "var(--color-primary-lucid)",
      },

      secondary: {
        DEFAULT: "var(--color-secondary)",
        shade: "var(--color-secondary-shade)",
        tint: "var(--color-secondary-tint)",
        light: "var(--color-secondary-light)",
        dark: "var(--color-secondary-dark)",
        opacity: "var(--color-secondary-opacity)",
        trans: "var(--color-secondary-trans)",
        lucid: "var(--color-secondary-lucid)",
      },

      tertiary: {
        DEFAULT: "var(--color-tertiary)",
        shade: "var(--color-tertiary-shade)",
        tint: "var(--color-tertiary-tint)",
        light: "var(--color-tertiary-light)",
        dark: "var(--color-tertiary-dark)",
        opacity: "var(--color-tertiary-opacity)",
        trans: "var(--color-tertiary-trans)",
        lucid: "var(--color-tertiary-lucid)",
      },

      success: {
        DEFAULT: "var(--color-success)",
        shade: "var(--color-success-shade)",
        tint: "var(--color-success-tint)",
        light: "var(--color-success-light)",
        dark: "var(--color-success-dark)",
        opacity: "var(--color-success-opacity)",
        trans: "var(--color-success-trans)",
        lucid: "var(--color-success-lucid)",
      },

      warning: {
        DEFAULT: "var(--color-warning)",
        shade: "var(--color-warning-shade)",
        tint: "var(--color-warning-tint)",
        light: "var(--color-warning-light)",
        dark: "var(--color-warning-dark)",
        opacity: "var(--color-warning-opacity)",
        trans: "var(--color-warning-trans)",
        lucid: "var(--color-warning-lucid)",
      },

      danger: {
        DEFAULT: "var(--color-danger)",
        shade: "var(--color-danger-shade)",
        tint: "var(--color-danger-tint)",
        light: "var(--color-danger-light)",
        dark: "var(--color-danger-dark)",
        opacity: "var(--color-danger-opacity)",
        trans: "var(--color-danger-trans)",
        lucid: "var(--color-danger-lucid)",
      },

      dark: {
        DEFAULT: "var(--color-dark)",
        shade: "var(--color-dark-shade)",
        tint: "var(--color-dark-tint)",
        light: "var(--color-dark-light)",
        dark: "var(--color-dark-dark)",
        opacity: "var(--color-dark-opacity)",
        trans: "var(--color-dark-trans)",
        lucid: "var(--color-dark-lucid)",
      },

      medium: {
        DEFAULT: "var(--color-medium)",
        shade: "var(--color-medium-shade)",
        tint: "var(--color-medium-tint)",
        light: "var(--color-medium-light)",
        dark: "var(--color-medium-dark)",
        opacity: "var(--color-medium-opacity)",
        trans: "var(--color-medium-trans)",
        lucid: "var(--color-medium-lucid)",
      },

      light: {
        DEFAULT: "var(--color-light)",
        shade: "var(--color-light-shade)",
        tint: "var(--color-light-tint)",
        light: "var(--color-light-light)",
        dark: "var(--color-light-dark)",
        opacity: "var(--color-light-opacity)",
        trans: "var(--color-light-trans)",
        lucid: "var(--color-light-lucid)",
      },

      step: {
        50: "var(--color-step-50)",
        100: "var(--color-step-100)",
        150: "var(--color-step-150)",
        200: "var(--color-step-200)",
        250: "var(--color-step-250)",
        300: "var(--color-step-300)",
        350: "var(--color-step-350)",
        400: "var(--color-step-400)",
        450: "var(--color-step-450)",
        500: "var(--color-step-500)",
        550: "var(--color-step-550)",
        600: "var(--color-step-600)",
        650: "var(--color-step-650)",
        700: "var(--color-step-700)",
        750: "var(--color-step-750)",
        800: "var(--color-step-800)",
        850: "var(--color-step-850)",
        900: "var(--color-step-900)",
        950: "var(--color-step-950)",
      },
    },
  },
[...]
};


```
