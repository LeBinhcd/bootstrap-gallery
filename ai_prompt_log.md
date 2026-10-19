# AI prompt log

- Asked AI to identify the Bootstrap utilities needed for a compact responsive layout: `d-flex`, `align-items-center`, `justify-content-between`, `gap-*`, `mb-*`, `py-*`, `rounded-pill`, and `shadow-sm`.
- Asked why Author Info should use Flexbox instead of `row`/`col`: it is a one-dimensional group that needs direct vertical centering and simple spacing.
- Asked how to replace legacy layout techniques: removed float and absolute positioning for layout; used Flexbox for Author Info and CSS Grid for the Mosaic Gallery.
- Asked how CSS Grid handles additional gallery images. With `grid-auto-rows`, new items automatically occupy the next available grid cell and create implicit rows when needed.
- Asked how `object-fit: cover` prevents gallery images from being stretched or distorted.
