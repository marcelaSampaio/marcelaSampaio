### Marcela Sampaio

I build the geometry layer underneath graphics software — the part that has to be *correct*, not just look right.

Software engineer with a background in Systems Analysis and Physics. Most of what I do is 2D and 3D geometry in the browser: product configurators, CAD-like editors, and the algorithms under them — polygon offsetting and booleans, transformations, hit testing, nesting, numerical tolerance, and the degenerate cases that break naive implementations.

Geometry that feeds manufacturing has to be right in millimetres, and it fails quietly: output that is wrong by two millimetres still looks exactly like the drawing. So I write the check alongside the algorithm.

#### Selected work

| | |
|---|---|
| **[looks-glassy](https://github.com/marcelaSampaio/looks-glassy)** | Refractive UI components for React and Angular. Physics-based SVG displacement maps with a framework-agnostic core and graceful fallbacks. TypeScript, MIT. |
| **[polygon-offset](https://github.com/marcelaSampaio/polygon-offset)** | Interactive demo of why the obvious offset algorithm is wrong. Moving vertices along the angle bisector puts the result 123.6px from the source polygon when you asked for 68; the robust pass lands at 0.0px error. |
| **[llm-outreach-pipeline](https://github.com/marcelaSampaio/llm-outreach-pipeline)** | Staged Rails pipeline: per-stage feature flags, LLM cost ceilings, swappable providers, and an experiment/variant framework for A/B testing prompts. |

#### Working with

`TypeScript` `Three.js` `WebGL` `Canvas 2D` `SVG` `Angular` `React` `Ruby on Rails` `Java` `PostgreSQL` `AWS`

#### Elsewhere

Available for freelance work on configurators, CAD-like tooling and geometry algorithms.

[marcela-sampaio.pages.dev](https://marcela-sampaio.pages.dev)
