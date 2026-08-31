# GenLayer Orbit Spinner

GenLayer Orbit Spinner is a dependency-free, production-ready loading system for GenLayer Portal and dApp interfaces. It uses layered orbital paths and a geometric core to express network activity, consensus, and transaction waiting in a compact, reusable visual primitive.

## Why it is useful for GenLayer

GenLayer interfaces frequently need clear loading feedback while a route loads, a wallet action is processed, or a transaction moves toward finality. This spinner provides a consistent GenLayer-inspired identity without requiring a JavaScript framework or a runtime dependency.

## Included variants

The demo shows compact, standard, large, and full-screen sizes. The asset works on both light and dark surfaces and includes reduced-motion behavior for users who prefer less animation.

| Variant | Recommended use |
| --- | --- |
| Compact | Buttons, cards, inline loading states |
| Standard | Panels, forms, and transaction status areas |
| Large | Dialogs and route transitions |
| Full-screen | Portal loading and long-running transaction states |

## Features

- Standalone animated SVG asset.
- CSS sizing helpers for compact, standard, large, and full-screen states.
- Light and dark surface examples.
- Accessible loading labels in the demo.
- `prefers-reduced-motion` support and a manual reduced-motion control.
- Copy SVG control for quick integration.
- Responsive mobile layout.
- No JavaScript dependency for the spinner asset itself.

## Demo

Open `demo.html` in a browser. The demo includes size variants, a light surface, a full-screen state, usage code, and interactive controls.

For a local preview, run:

    python -m http.server 8080

Then open:

    http://127.0.0.1:8080/demo.html

## Usage

Use the SVG directly:

    <img class="gl-spinner gl-spinner--md" src="genlayer-orbit-spinner.svg" alt="Loading">

Use the CSS helpers:

    <link rel="stylesheet" href="spinner.css">
    <img class="gl-spinner gl-spinner--sm" src="genlayer-orbit-spinner.svg" alt="Loading">

Available classes are `gl-spinner--sm`, `gl-spinner--md`, `gl-spinner--lg`, and `gl-spinner--xl`.

## Accessibility and motion

Loading images should include a useful `alt` value when they communicate status. The demo also includes visually hidden status text. The CSS honors the user's `prefers-reduced-motion` setting, and the demo provides a manual reduced-motion toggle.

## Repository structure

    genlayer-orbit-spinner.svg   Core animated SVG asset
    spinner.css                  Sizing and motion helpers
    demo.html                    Responsive interactive demo
    preview-light-dark.webp      Preview image on light and dark surfaces
    SUBMISSION_COPY.md           Resubmission title, description, and evidence

## Evidence

Repository: https://github.com/0ogodboyo0/genlayer-orbit-spinner

SVG source: https://github.com/0ogodboyo0/genlayer-orbit-spinner/blob/main/genlayer-orbit-spinner.svg

Demo source: https://github.com/0ogodboyo0/genlayer-orbit-spinner/blob/main/demo.html

Preview: https://github.com/0ogodboyo0/genlayer-orbit-spinner/blob/main/preview-light-dark.webp

## License

See `LICENSE` for the project license.
