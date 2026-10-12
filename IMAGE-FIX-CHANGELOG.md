# Image sizing fix — 12 October 2026

The Home and About pages previously rendered some stock photography with a fixed
HTML height attribute but a constrained width. That could distort the displayed
aspect ratio on both desktop and mobile screens.

## Fixed without redesigning

- Homepage insight cards: controlled 8:5 landscape crop (16:10 on phones) with
  `object-fit:cover`, keeping natural subject proportions rather than stretching.
- About page's introductory photograph: 5:4 (4:3 on phones), cropped without distortion.
- About page's lower photograph: responsive 4:3 crop without distortion.
- Homepage advocate photograph: existing object-fit treatment preserved.
- The design, colours, typography, content, contact links, SEO and branding are unchanged.

These image links are hosted by Pexels; connection is needed in production.
