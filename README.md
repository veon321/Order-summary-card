# Frontend Mentor - Order summary card solution

This is a clean, responsive, and modern solution to the Order summary card challenge on Frontend Mentor.

## The challenge

The challenge was to build an order summary card component and get it looking as close to the design as possible using HTML and CSS. The component needed to be fully responsive, handling both mobile and desktop layouts seamlessly while implementing professional interactive elements (buttons and links with custom hover states).

## Links

- Solution URL: [https://github.com/veon321/Order-summary-card](https://github.com/veon321/Order-summary-card)
- Live Site URL: [https://veon321.github.io/Order-summary-card/](https://veon321.github.io/Order-summary-card/)

## Built with

- Semantic HTML5 markup (utilizing `<main>`, `<article>`, and native accessible `<button>` tags for interactive states)
- CSS Custom Properties (Variables) with strict adherence to the design system color constants
- Flexbox layout (leveraging flexible column arrangements and automated `gap` spacing)
- Modern CSS Math Functions (`clamp()` used extensively for fluid typography, dynamic paddings, inner gaps, and component scaling)
- Mobile-first approach transitioning into a completely fluid desktop layout
- Google Fonts (Red Hat Display)

## Features

- **No Media Queries (`@media`):** The entire component's responsiveness is completely fluid. By utilizing a smart `width: clamp()` on the card container, the layout scales down safely to a crisp 280px minimum for mobile viewports, while organically settling at its maximum 450px desktop boundary without hardcoded layout breakpoints.
- **Micro-interactions & Active States:** - **Dynamic Buttons:** The main "Proceed to Payment" call-to-action is built using semantic buttons, featuring a custom color shift on hover and a deep, soft brand-colored drop shadow (`box-shadow`) matching the reference design.
  - **Clean Cancel State:** The "Cancel Order" button has been cleanly reset to remove browser-default chrome, rendering as purely transparent clickable text that subtly shifts to darker tones upon user interaction.
- **Ultrapłynny Layout Spacing (Fluid Paddings & Gaps):** Rather than implementing static padding or margins, internal elements utilize `clamp()` functions for inner gaps and paddings. The design shrinks seamlessly when space is restricted, preventing any text overflow or visual breakage.
- **Flawless Asset Management & Styling:** The decorative hero asset (`illustration-hero.svg`) is set to `display: block` with a full-width rule, making it conform exactly to the card's boundary and eliminating unwanted browser text-baseline space underneath. The background wave pattern is locked perfectly via `background-size: contain` and `repeat-x` across the body viewport.
