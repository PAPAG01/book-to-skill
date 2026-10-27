# Website Development Criteria

Apply these criteria **first**, before planning or writing any code, for every website or web page built in this repository. Then continue with the rest of the process.

## Design quality

- **Polished and responsive.** Build an interface that works well at every screen size, from phones up to wide desktops.
- **Clear visual hierarchy.** It should be obvious what matters most on each page and where to look next.
- **Consistent spacing and components.** Use a shared spacing scale, type scale, and reusable components rather than one-off styles.
- **Thoughtful interaction details.** Hover, focus, active, loading, empty, and error states are designed, not left as defaults.
- **Purposeful animation only.** Animate only when it helps users understand an action or makes the interface feel more responsive. Respect `prefers-reduced-motion`.
- **Fast.** Keep the page light: optimized images, minimal JavaScript, no unnecessary dependencies.
- **Accessible.** Semantic HTML, keyboard navigation, visible focus, sufficient color contrast (WCAG 2.1 AA), meaningful alt text and labels.
- **Easy to use on mobile.** Touch targets of at least 44×44px, readable text without zooming, and no horizontal scrolling.

## Before calling a site done

- [ ] Checked at phone, tablet, and desktop widths
- [ ] Keyboard-only walkthrough works, focus is always visible
- [ ] Contrast checked; animations respect reduced motion
- [ ] Page loads quickly on a mobile connection
