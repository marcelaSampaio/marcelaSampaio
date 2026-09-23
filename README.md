### Marcela Prado

Senior full-stack engineer and Tech Lead. I build the parts that have to be *correct*, not just look right.

Eight-plus years in software, with a background in Systems Analysis and Physics. I build and run production web platforms end to end — TypeScript with Angular or React, Ruby on Rails, Node, Java and Python over PostgreSQL and AWS: API design, background job pipelines, data ingestion, and the retries, idempotency and reconciliation that keep an integration alive unattended.

The specialty underneath all of that is 2D and 3D geometry in the browser: product configurators, CAD-like editors, polygon offsetting and booleans, transformations, hit testing, nesting, numerical tolerance, and the degenerate cases that break naive implementations.

Geometry that feeds manufacturing has to be right in millimetres, and it fails quietly: output that is wrong by two millimetres still looks exactly like the drawing. So I write the check alongside the algorithm — and I bring that habit to everything else.

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

#### Writing

I write up the failure modes I have had to design around — idempotency, retries, migrations that cannot take a lock, caches that are allowed to be wrong. 25 posts at [pradom.substack.com](https://pradom.substack.com).

- [Soft Deletes in Rails, By Hand: Visibility Is a Predicate](https://pradom.substack.com/p/soft-deletes-in-rails-by-hand-visibility) — no gems, and a measured rule for when a partial index actually earns its place
- [Idempotency in Ruby on Rails](https://pradom.substack.com/p/idempotency-in-ruby-on-rails-why) — the written half of `replayable-ingest`
- [Designing Database Indexes Like a Systems Engineer](https://pradom.substack.com/p/designing-database-indexes-like-a)

#### Elsewhere

Available for freelance work: product engineering and technical leadership — APIs, job pipelines and integrations built to survive production — plus the geometry and 3D work most teams cannot staff.

[marcela-sampaio.pages.dev](https://marcela-sampaio.pages.dev) · [pradom.substack.com](https://pradom.substack.com)
