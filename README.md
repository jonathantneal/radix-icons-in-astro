# Radix Icons in Astro

[**Radix Icons**](https://icons.modulz.app/) are a crisp set of 15×15 icons designed by the [Modulz](https://modulz.app/) team.

This demonstration utilizes them as pure Astro components.

```astro
---
import Icon from '@modulz/radix-icons/astro'
---
<Icon.ArrowLeftIcon aria-label="Arrow Left" />
<Icon.ArrowRightIcon aria-label="Arrow Right" />
<Icon.CheckCircledIcon aria-label="Check Circled" size="30" />
<Icon.CrossCircledIcon aria-label="Cross Circled" />
```

```html
<svg viewBox="0 0 15 15" aria-label="Arrow Left"><!-- SVG data for Arrow Left --></svg>
<svg viewBox="0 0 15 15" aria-label="Arrow Right"><!-- SVG data for Arrow Right --></svg>
<svg viewBox="0 0 15 15" aria-label="Check Circled"><!-- SVG data for Check Circled --></svg>
<svg viewBox="0 0 15 15" aria-label="Cross Circled" width="30" height="30"><!-- SVG data for Cross Circled --></svg>
```
