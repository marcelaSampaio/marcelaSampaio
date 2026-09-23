### Marcela Sampaio

I build the geometry layer underneath graphics software — the part that has to be *correct*, not just look right.

Eight-plus years in software, with a background in Systems Analysis and Physics. Most of what I do is 2D and 3D geometry in the browser: product configurators, CAD-like editors, and the algorithms under them — polygon offsetting and booleans, transformations, hit testing, nesting, numerical tolerance, and the degenerate cases that break naive implementations.

Geometry that feeds manufacturing has to be right in millimetres, and it fails quietly: output that is wrong by two millimetres still looks exactly like the drawing. So I write the check alongside the algorithm.

#### Selected work

| | |
|---|---|
| **[looks-glassy](https://github.com/marcelaSampaio/looks-glassy)** | Refractive UI components for React and Angular. Physics-based SVG displacement maps with a framework-agnostic core and graceful fallbacks. TypeScript, MIT. |
| **[threejs-product-configurator](https://github.com/marcelaSampaio/threejs-product-configurator)** | A 3D product configurator with no model file. Geometry generated from millimetre parameters, and the same numbers produce the 2D cutting layout with seam allowances measured back to the sewing line. |
| **[polygon-offset-exact](https://www.npmjs.com/package/polygon-offset-exact)**<br>`npm i polygon-offset-exact` | Polygon offsetting that lands at the distance you asked for — and the function that proves it. TypeScript, zero dependencies, 57 tests. The angle-bisector method most people write is off by 205% on a star; this one by 1e-14. [Source](https://github.com/marcelaSampaio/polygon-offset). |
| **[nesting-playground](https://github.com/marcelaSampaio/nesting-playground)** | Bin packing with the constraints fabric imposes — roll width, grain direction, spacing. Each one is a control, so its cost shows up in metres: dropping the grain lock takes the default marker from 2.54 m to 2.44 m. |
| **[geometry-for-design-tools](https://github.com/marcelaSampaio/geometry-for-design-tools)** | Four pieces of 2D geometry every CAD-like editor needs, each written around its failure mode rather than its formula. Everything on the page is draggable; every number is computed live. |
| **[llm-outreach-pipeline](https://github.com/marcelaSampaio/llm-outreach-pipeline)** | Staged Rails pipeline: per-stage feature flags, LLM cost ceilings, swappable providers, and an experiment/variant framework for A/B testing prompts. |

#### Working with

`TypeScript` `Three.js` `WebGL` `Canvas 2D` `SVG` `Angular` `React` `Ruby on Rails` `Java` `PostgreSQL` `AWS`

#### Elsewhere

Available for freelance work on configurators, CAD-like tooling and geometry algorithms.

[marcela-sampaio.pages.dev](https://marcela-sampaio.pages.dev)
