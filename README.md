# CSS Box

A modern KISS CSS toolbox.

## Contents

- `vendor/normalize/normalize.css`: normalize.css `8.0.1`
- `vendor/fontawesome/css/all.min.css`: Font Awesome Free `7.2.0`
- `css/kiss-toolbox.css`: modernized KISS toolbox with legacy class compatibility
- `css-box.css`: single CSS entry point
- `examples.html`: kitchen-sink examples page

## Usage

```html
<link rel="stylesheet" href="css-box.css">
```

## Live Demo

- Project home: https://monkeytime.github.io/css-box/
- Examples page: https://monkeytime.github.io/css-box/examples.html

## Browser Support

CSS Box targets modern evergreen browsers: current Chrome, Edge, Firefox, and Safari, plus the last two major versions where practical. The stylesheet avoids `@layer` so older browsers do not drop whole sections, includes fallbacks for `color-mix()`, and keeps physical fallbacks for key logical sizing utilities.

## License

MIT.

Legacy helpers such as `.u50`, `.p2`, `.txtc`, `.bg-blu`, `.btn`, `.alert`, and `.hidden-phone` remain available. The toolbox also adds modern helpers such as `.container`, `.grid`, `.grid-3`, `.stack`, `.cluster`, `.flex`, `.gap3`, `.radius`, `.shadow`, `.aspect-16-9`, and `.visually-hidden`.

The `examples.html` page demonstrates grids, forms, alerts, buttons, cards, badges, tables, progress bars, pagination, dashboard stats, pricing cards, tabs, breadcrumbs, timeline, media object, static modal, skeleton loading, and utilities.
